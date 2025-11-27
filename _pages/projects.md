---
layout: archive
permalink: /projects/
title: ""
date: 2014-06-02T15:05:16-04:00
modified: 2016-01-04T16:38:17-05:00
excerpt: 
ads: false
fullwidth: true
tiles: true
feature:
  visible: false
  headline: "Featured Work"
  category: project
---

{{ page.excerpt | markdownify }}
<style> 
  h1 { text-align: left; font-weight: bold; font-size: 30px; letter-spacing: 3px; color: blue;text-transform: uppercase;}
  a.Project:link { color: green; background-color: transparent; text-decoration: none; } a.Project:visited { color: blue; background-color: transparent; text-decoration: none; } a.Project:hover { color: blue; background-color: transparent; text-decoration: underline; } a.Project:active { color: yellow; background-color: transparent; text-decoration: underline; } </style>

<h1> 🛠️ Self-Supervised Projects 🔧 </h1>
<hr>

## Lidar Obstacle Detection with ROS
* <b>Goal</b>:  use various algorithms on Point Cloud data such as Voxel Grid filtering, RANSAC segmentation, and Euclidean Clustering with KD-Tree to detect obstacles
* <b> Pipeline </b>

  <img src="https://somikdhar729.github.io/images/lidar_pipeline.png" style="width: auto; max-width: 100%; height: auto;"/>

* <b> Results </b> 
The following animation shows the segmented point clouds - obstacles (in yellow) and road (in green)

    <img src="https://somikdhar729.github.io/images/pcl_gif.gif" alt="Drawing" style="width: 50%;"/>

## Autonomous Maze Solver Robot
* Developed an autonomous maze-solving robot using TurtleBot3 and ROS <br>
* Integrated RPLIDAR sensor for real-time obstacle detection and avoidance <br>
* Implemented intelligent wall-following and search algorithms<br>
* Leveraged TurtleBot3 for rapid prototyping and navigation strategy testing <br>

<a href = "https://somikdhar729.github.io/images/Video 1.mp4" target="_blank" rel="noopener noreferrer" class = "Project"><i>(Video 1)</i> <a href = "https://somikdhar729.github.io/images/Video 2.mp4" target="_blank" rel="noopener noreferrer" class = "Project"><i>(Video 2)</i> <a href = "https://somikdhar729.github.io/images/Video 3.mp4" target="_blank" rel="noopener noreferrer" class = "Project"><i>(Video 3)</i>  

## Real-Time Mask Detection using Convolutional Neural Networks (CNN)
* Developed a real-time facial mask detection system using a custom Convolutional Neural Network (CNN) model built with TensorFlow <br>
* Designed and trained CNN architecture to accurately identify the presence of masks on faces in video streams <br>
* Optimized model for real-time performance, achieving <100ms inference time per frame on webcam feeds <br>
* Achieved 96% accuracy in detecting masked individuals in real-world conditions, ensuring reliable monitoring <br>
* Demonstrated expertise in computer vision, deep learning, real-time analytics, and deploying AI solutions <br>
(<a href = "https://www.youtube.com/watch?v=7wAw15L6rPk" target="_blank" rel="noopener noreferrer" class = "Project"><i>Video</i>)
(<a href = "https://github.com/somikdhar729/Mask_Recognization" target="_blank" rel="noopener noreferrer" class = "Project"><i>Code</i>)

<h1> 🎓 Mentored Projects 🎓</h1>
<hr>
 
## VR-Based Smart Whack-A-Mole: A Benchmarking Platform for Target Prediction Algorithms
<i> Aug'22 - Dec'22</i><br>

<b>Overview:</b> Developed a VR-based Whack-A-Mole benchmarking platform in Unity, integrated with Oculus and Leap Motion IR for egocentric hand tracking.
<b>Contribution</b>
* Collected a large-scale egocentric hand-target dataset from 4 users (2,900+ trials at 100Hz), including 21-finger centroid trajectories across scaled inter-target distances (0.7–1.0).
* Implemented and benchmarked multiple target prediction algorithms: analytical velocity-based, DTW (91% test accuracy), and LSTM/RNN models (up to 90% real-time AI scores).
*Designed standardized evaluation metrics: prediction speed distributions, multi-class accuracy, confidence scores, and trajectory point MAE (0.0018).
* Conducted robust real-time testing (100 trials/model at unseen scales 0.58–0.9), demonstrating LSTM models outperform DTW in efficiency and real-time performance.
* Created an interactive game environment for quantitative benchmarking of prediction algorithms, enabling intuitive evaluation of egocentric hand tracking models.
(<a href = "https://drive.google.com/file/d/1b5OidOE3OiEDEcAab8-1oqTwOLCEurrM/view?usp=share_link" target="_blank" rel="noopener noreferrer" class = "Project"><i>Paper</i>)
  
### Modelling and Control of a Quadrotor System

*Final Year Project, IIEST Shibpur* \| August 2020 – May 2021<br>
<i>Supervisors: Dr. Ashoke Sutradhar, Professor, IIEST Shibpur </i><br>

<b>Overview: </b> Design a dynamic simulation model for a stable flight control for a quadcopter in SIMULINK
<b>Contribution</b>
* Formulated the 6-DOF motion equations using the Newton-Euler method, modeling thrust, drag, gyroscopic effects, and actuator limitations.
* Designed a modular Simulink plant model with realistic constraints including motor saturation, thrust–weight ratio (>2:1), and body–inertial frame transformations.
* Designed and tuned cascaded PID controllers for altitude, attitude (roll/pitch), and yaw, achieving stable tracking under step, ramp, and multi-axis trajectory inputs.
* Simulated realistic flight behaviors including hovering, altitude ramps to 5m in <10s, 12° attitude maneuvers, and 3D inertial trajectories, validating controller robustness across coupled dynamics.
<br>(<a href = "https://somikdhar729.github.io/pdfs/UG-Proj Final Report_AS_Modelling and Control of Quadrotor System 2020-21.pdf" target="_blank" rel="noopener noreferrer" class = "Project"><i>Report</i>)

### Stabilization of Single Link Manipulator

*IIEST Shibpur* \| December 2019 – January 2020<br>
<i>Supervisor: Dr. Aparajita Sengupta, Professor, IIEST Shibpur</i><br>

<b>Overview:</b> Developed a nonlinear dynamic model and stabilization controller for a single-link robotic manipulator using Lagrangian mechanics

* Derived the nonlinear dynamics using Lagrangian and Euler–Lagrange methods, obtaining the second-order system
$\tau = ml^2\ddot\theta + mgl\sin\theta$

* Linearized the system around the unstable equilibrium at θ = 45°, producing a state-space model with an unstable pole at +2.081 rad/s
* Designed and tuned a PID controller (Kp=54.5, Ki=15.3, Kd=48.5, N=60) to stabilize the manipulator for target angles between 30°–90° from initial states up to 0°–90°, achieving settling times under 3 seconds
* Validated performance through multi-angle step responses (0→45°, 0→90°, 60→45°, 90→30°), demonstrating zero steady-state error and low overshoot beyond the linearization region.
(<a href = "https://somikdhar729.github.io/pdfs/Stabilisation of single link manipulator- ASG.pdf" target="_blank" rel="noopener noreferrer" class = "Project"><i>Report</i>)













