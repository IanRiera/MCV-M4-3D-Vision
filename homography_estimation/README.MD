# Week 2

### [Report](https://github.com/IanRiera/MCV-M4-3D-Vision/blob/master/homography_estimation/M4_Lab2_Team7.pdf)

In this project, the homography relating two images is estimated from the key-point correspondences between them. After obtaining the homography, different applications are tested: image mosaic, camera calibration, logo detection and logo replacement.

The code is presented in the Jupyter Notebook **lab2-team7.ipynb**. 

## Task 1: Homography Estimation with the DLT Algorithm
* Compute image correspondences
* Estimate the homography between image pairs (RANSAC, normalized DLT algorithm)

## Task 2: Application - Image Mosaics
* Estimate homography
* Transform images and fuse them to form a mosaic

## Task 3: Refinement of the Estimated Homography with the Gold Standard Algorithm
* Least squares to minimize the geometric cost
* Levenberg-Marquardt algorithm

## Task 4 (Optional): Application - Calibration with a Planar Pattern and Augmented Reality
* Camera calibration with a planar pattern using Zhang's algorithm
* Insert a virtual object maintaing the perspective sense with the rest of the scene

## Task 5 (Optional): Application - Logo Detection
* Manual detection (manually select keypoints to estimate homography)
* Automatic detection (compute image correspondences/keypoints and estimate homography)

## Task 6 (Optional): Application - Logo Replacement
* Use estimated homography to project new logos onto the target images
