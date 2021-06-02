# Week 5

### [Report](https://github.com/oscarlorente/3D-Reconstruction-of-Urban-Scenes/blob/main/lab5/M4_Lab5_Team7.pdf)

In this project, we apply scene 3D reconstruction from non-calibrated images with a stratified method (recovery of camera matrices and a sparse set of 3D points), by applying the Structure from Motion (SfM) approach on real data. Specifically, we begin with a projective reconstruction and then refine it progressively to an affine and finally a metric reconstruction. We also implemented the resection method, which estimates a camera matrix P from a set of 2D-3D point correspondences by using the DLT algorithm.

The code is presented in the **code** folder, being **code/lab5.py** the main function. 

## Task 1: Fundamental Matrix Estimation
* Compute image correspondences
* Estimate the fundamental matrix (F) between image pairs using the RANSAC-based robust 8-point normalized algorithm

## Task 2: Projective Reconstruction
* Compute projective cameras from F
* Projective triangulation for 3D structure

## Task 3: Affine Rectification
* Plane at infinity described by three vanishing points

## Task 4: Metric Rectification
* Metric reconstruction (Cholesky factorization)

## Task 5: Reprojection Error
* Reprojective, affine and euclidean error

## Task 6: Bundle Adjustment
* Simultaneously refine the 3D coordinates describing the scene geometry, the parameters of the motion and the optical characteristics of the camera
