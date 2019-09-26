# ECE767
Multitarget Tracking and Multisensor Information Fusion

Assignment 1 

Implement a nearest-neighbor EKFor CMKFtracker for the following scenario:

Target:

Single target moving with a constant velocity model.

Sensor: 

Position: [1000 500], 
Stationary (i.e., velocity = [0 0])
Measurements: range and azimuth
Error standard deviation: range = 10 m, azimuth = 0.01 rad
Sampling time = 2s
Pd = 0.9
False alarm density (lambda)= 1e-4
Coverage: range [0 to 10000]m
azimuth [-pi to pi]

Tracker:

Assume track is already initialized.
Use simple nearest-neighbor data association (get the closest measurement)
Use EKF or CMKF filtering

Performance Evaluation:

Evaluate RMSE In the report,

please include the following:

Matlab code 
Plot showing the truth and estimated trajectories 
Plot showing the RMSE

Due date: October17, 2019
