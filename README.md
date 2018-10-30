# CarND-Extended-Kalman-Filter-Project
This repository contains code and other files required as part of the Extended Kalman Filter project of the Self Driving Engineer Term 2 course.
The code changes were made to the following 3 files:
* tools.cpp - RMSE and Jacobian Matrix methods were implemented.
* FusionEKF.cpp - Kalman Filter variables and covariance matrices were initialized.
* kalman_filter.cpp - predict, update and updateEKF methods were implemented.

The application can be compiled using:
* `mkdir build`
* `cd build && cmake ..`
* `make`
* `./ExtendedEKF`
