# XPLORER Wrench Estimator
Repo to estimate wrench for XPLORER

## Description

This repo has the code for novel external wrench estimation algorithm developed and the corresponding interaction controller, an admittance controller, designed by using the wrench estimates.

## Dependencies

You need to have the following packages installed in your system:

[SQUEEZE Custom Messages](https://github.com/ASU-RISE-Lab/squeeze_custom_msgs)

## Build

```
cd ~/colcon_ws/src
git clone git@github.com:ASU-RISE-Lab/squeeze_wrench_estimator.git
cd ~/colcon_ws
colcon build --packages-select squeeze_wrench_estimator
```

## Launching the node

```
ros2 run squeeze_wrench_estimator wrench_estimator
```
