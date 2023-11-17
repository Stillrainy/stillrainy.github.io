---
title: 'Vision-based Force Estimation of Surgical Robot'
date: 2023-09-30
permalink: /posts/2023/09/30/
tags:
  - Neural Network
  - Computer Vision
  - Surgical Robot
---

In scenarios where access to robot kinematic and camera parameters data is not available, this research devises an alternative approach to estimate a normalized 3D end-effector position from video data based on extracted keypoints from DeepLabCut. The movement of the end-effector is tracked from stereoscopic video of the surgical robot and then deep neural network (DNN) and graph neural network (GNN) are used to estimate the relative depth of the end-effector. 

## Sample of Dataset
![dVRK Data](../images/C_M1_T1_4_L.jpg)

## Keypoints Tracking and Usage in GNN
![Keypoints](../images/keypoints.png)
![gnn](../images/gnn-nodes.png)

## Cropped and Enhanced Images for Contact Deteaction
![cropper](../images/crop-concat.png)

## 2D Keypoints Coordinates -> 3D Positions of the End-effector
![cropper](../images/M2_R_V2_2.png)
