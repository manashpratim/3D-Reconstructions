# 3D-Reconstructions
3D Reconstruction using Triangulation, Photometric Stereo and Deep Learning
# Description

## HW4
•	Implemented the 8-point algorithm to estimate the fundamental matrix from corresponding points in two images.

•	With the fundamental matrix and calibrated intrinsics, computed the essential matrix and used this to compute a 3D metric reconstruction from 2D correspondences using triangulation.

•	Implemented a method to automatically match points, taking advantage of epipolar constraints and made a 3D visualization of the results. Finally, implemented RANSAC and bundle adjustment to further improve the algorithm.

## HW6

•	Determined the shape of a person’s face using both calibrated and uncalibrated photometric vision (assuming Lambertian object and Orthographic Camera).

## ResDepth
•	Proposed a deep learning architecture (ResDepth), an encoder-decoder self-supervised network, to compute disparity of images and videos.

• Trained the network using the stereo pairs from the KITTI dataset. Computed loss using a combination of L1 and SSIM loss.

•	Beat the state of the art Monodepthv2 self-supervised model (baseline model) in all 7-performance metrics. 

• ResDepth is inspired from https://github.com/ialhashim/DenseDepth and https://github.com/nianticlabs/monodepth2.

**Note: This project is part of my Homeworks. Current CMU students please refrain from going through the codes.**
