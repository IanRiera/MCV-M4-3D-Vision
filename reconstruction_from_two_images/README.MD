# Week 4

### [Report](https://github.com/IanRiera/MCV-M4-3D-Vision/blob/master/reconstruction_from_two_images/M4_Lab4_Team7.pdf)

In this project, we triangulate the matching correspondences between two views of the same scene using DLT. We compute the camera matrices of these images given the Fundamental Matrix and the Intrinsic Matrix, and evaluate the triangulation method by estimating the reprojection error. We also apply the triangulation in order to create a 3D reconstruction from two views. 

The second part of the project focuses on computing depth maps using local methods (SSD, NCC) and implementing bilateral weights on this mapping.

We also implemented two optional tasks: stereo computation with Belief Propagation and new view synthesis (morphing technique).

The code is presented in the Jupyter Notebook **lab4.ipynb**. 

## Task 1: Triangulation
* DLT algorithm to triangulate 3D points from 2D correspondences and camera matrices

## Task 2: Reconstruction from Two Views
* Compute 2D correspondences, fundamental matrix and camera projection matrices
* Use the camera matrices to triangulate 3D points and perform a 3D reconstruction

## Task 3: Depth Map Computation
* Disparity maps using SSD or NCC
* Bilateral weights

## Task 4 (Optional): Stereo Computation with Belief Propagation
* Treat the image as a graph and approach the problem of recovering an accurate disparity map as an energy minimization problem
* Insert a virtual object maintaing the perspective sense with the rest of the scene

## Task 5 (Optional): New View Synthesis
* Interpolation method (two parallel views)
