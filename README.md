# 3D-Reconstructions
3D Reconstruction using Triangulation, Photometric Stereo and Deep Learning
## Description

### 3D Reconstruction using Triangulation
•	Implemented the 8-point algorithm to estimate the fundamental matrix from corresponding points in two images.

•	With the fundamental matrix and calibrated intrinsics, computed the essential matrix and used this to compute a 3D metric reconstruction from 2D correspondences using triangulation.

•	Implemented a method to automatically match points, taking advantage of epipolar constraints and made a 3D visualization of the results. Finally, implemented RANSAC and bundle adjustment to further improve the algorithm.

• Codes are in hw4.zip and elaborate project description is in hw4.pdf 

![Image 1](https://github.com/manashpratim/3D-Reconstructions/blob/master/fig2.png)
**3D Point Clouds**
<img align="left" width="400" height="500" src="https://github.com/manashpratim/3D-Reconstructions/blob/master/q1.PNG">
<img align="rights" width="400" height="500" src="https://github.com/manashpratim/3D-Reconstructions/blob/master/q3.png">

### 3D Reconstruction using Photometric Stereo

•	Determined the shape of a person’s face using both calibrated and uncalibrated photometric vision (assuming Lambertian object and Orthographic Camera).

• Codes are in hw6.zip and elaborate project description is in hw6.pdf 

**Calibrated Photometric Vision**
![Calibrated Photometric Vision](https://github.com/manashpratim/3D-Reconstructions/blob/master/albnorm.png)
**Uncalibrated Photometric Vision**
![Uncalibrated Photometric Vision](https://github.com/manashpratim/3D-Reconstructions/blob/master/albnorm2.png)

### 3D Reconstruction using Deep Learning (ResDepth)

•	Proposed a novel deep learning architecture (ResDepth) consisting of an encoder-decoder self-supervised network, to compute disparity of images and videos.

• Trained the network using the stereo pairs from the KITTI dataset. Computed loss using a combination of L1 and SSIM loss.

•	Beat the state of the art Monodepthv2 self-supervised model (baseline model) in all 7-performance metrics. 

• ResDepth is inspired from DenseDepth (https://github.com/ialhashim/DenseDepth) and MonoDepthV2 (https://github.com/nianticlabs/monodepth2).

• Detailed report of the project is in ResDepthReport.pdf, code is in ResDepth_Manash.ipynb and a video of the results of the model is available at https://github.com/manashpratim/3D-Reconstructions/blob/master/project%20video.mp4.

• This is a group project. Here I have listed my contributions only.

#### ResDepth Architecture

![ResDepth Architecture](https://github.com/manashpratim/3D-Reconstructions/blob/master/architecture.PNG)

<img align="left" width="400" height="300" src="https://github.com/manashpratim/3D-Reconstructions/blob/master/encoder.PNG">

<p align="right">
  <img width="400" height="300" src="https://github.com/manashpratim/3D-Reconstructions/blob/master/decoder.PNG">
</p>


### Disparity Maps
<p align="center">
  <img width="460" height="500" src="https://github.com/manashpratim/3D-Reconstructions/blob/master/pics.PNG">
</p>


**Note: This project is part of my Homeworks. Current CMU students please refrain from going through the codes.**
