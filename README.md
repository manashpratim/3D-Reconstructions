# 3D-Reconstructions
3D Reconstruction using Triangulation, Photometric Stereo and Deep Learning
# Description

## HW4
•	Implemented the 8-point algorithm to estimate the fundamental matrix from corresponding points in two images.

•	With the fundamental matrix and calibrated intrinsics, computed the essential matrix and used this to compute a 3D metric reconstruction from 2D correspondences using triangulation.

•	Implemented a method to automatically match points, taking advantage of epipolar constraints and made a 3D visualization of the results. Finally, implemented RANSAC and bundle adjustment to further improve the algorithm.
![Image 1](https://github.com/manashpratim/3D-Reconstructions/blob/master/fig2.png)
**3D Point Clouds**
<img align="left" width="400" height="500" src="https://github.com/manashpratim/3D-Reconstructions/blob/master/q1.PNG">
<img align="rights" width="400" height="500" src="https://github.com/manashpratim/3D-Reconstructions/blob/master/q3.png">

## HW6

•	Determined the shape of a person’s face using both calibrated and uncalibrated photometric vision (assuming Lambertian object and Orthographic Camera).
**Calibrated Photometric Vision**
![Calibrated Photometric Vision](https://github.com/manashpratim/3D-Reconstructions/blob/master/albnorm.png)
**UnCalibrated Photometric Vision**
![UnCalibrated Photometric Vision](https://github.com/manashpratim/3D-Reconstructions/blob/master/albnorm2.png)

## ResDepth
•	Proposed a deep learning architecture (ResDepth), an encoder-decoder self-supervised network, to compute disparity of images and videos.

• Trained the network using the stereo pairs from the KITTI dataset. Computed loss using a combination of L1 and SSIM loss.

•	Beat the state of the art Monodepthv2 self-supervised model (baseline model) in all 7-performance metrics. 

• ResDepth is inspired from DenseDepth (https://github.com/ialhashim/DenseDepth) and MonoDepthV2 (https://github.com/nianticlabs/monodepth2).

**ResDepth Architecture**
![ResDepth Architecture](https://github.com/manashpratim/3D-Reconstructions/blob/master/architecture.PNG)

![Encoder Architecture](https://github.com/manashpratim/3D-Reconstructions/blob/master/encoder.PNG)

![Decoder Architecture](https://github.com/manashpratim/3D-Reconstructions/blob/master/decoder.PNG)

**Disparity Maps**
![Disparity Maps](https://github.com/manashpratim/3D-Reconstructions/blob/master/pics.PNG)

**Note: This project is part of my Homeworks. Current CMU students please refrain from going through the codes.**
