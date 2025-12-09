---
layout: archive
permalink: /work/
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
  category: work
---
 




<hr>
 <style>
h1 {
  text-align: center;
  text-transform: uppercase;
  font-size: 36px;
  letter-spacing: 3px;
  color: #0066cc;}
   
  a.Project:link { color: black; background-color: transparent; text-decoration: none; } a.Project:visited { color: black; background-color: transparent; text-decoration: none; } a.Project:hover { color: red; background-color: transparent; text-decoration: underline; } a.Project:active { color: yellow; background-color: transparent; text-decoration: underline; }
  
   a.Project1:link { color: blue; background-color: transparent; text-decoration: none; } a.Project1:visited { color: blue; background-color: transparent; text-decoration: none; } a.Project1:hover { color: green; background-color: transparent; text-decoration: underline; } a.Project1:active { color: yellow; background-color: transparent; text-decoration: underline; }
   
h2 {
  text-align: left;
  text-transform: uppercase;
  font-size: 20px;
  letter-spacing: 5px;
  color: black;
font-weight: bold;}
</style>

{{ page.excerpt | markdownify }}
<h1> Professional Experience </h1>
<h2> Ai & Perception Engineer </h2>
<I> Feb'25 - Present </I>

* Designed and deployed real-time vision + control pipelines for UAV tracking, autonomous landing, and perception-guided navigation under strict edge-compute constraints.
* Built low-latency video streaming systems (GStreamer + RTSP/UDP), sustaining 27–28 FPS from a 30 FPS camera feed on embedded platforms.
* Implemented multi-core and multi-threaded optimizations in Python/C++ to reduce perception-to-actuation latency by 30%.
* Worked across Jetson (Xavier/Orin), Raspberry Pi, and custom camera modules, contributing to sensor integration, camera evaluation, and model optimization for RGB + thermal pipelines.
* Currently exploring GNSS-denied autonomy, focusing on early-stage research into vision-based navigation for UAVs.

<h1> Research Experience </h1>
<h2> 🎓👨‍🔬Graduate Assitant </h2> <img src="https://somikdhar729.github.io/images/ai4ce_new_block_trans.png" alt="Drawing" width="150" height="150" align="right"/>
<I> Jan'23 - May'24</i><br>
<i><a href = "https://ai4ce.github.io/" target="_blank" rel="noopener noreferrer" class="Project"> AI4CE Lab,</a> New York University</i><br>

**Supervisor**: <a href="https://engineering.nyu.edu/faculty/chen-feng" target="_blank" rel="noopener noreferrer" class = "Project">Dr. Chen Feng, NYU </a>

* Developed and prototyped video-based VPR pipelines using CNN encoders, NetVLAD descriptors, and sequential matching for GPS-denied navigation.
* Implemented multiple VPR algorithms (NetVLAD, SeqMatchNet, SeqNet) and built tooling for sequence construction, temporal feature aggregation, and distribution-based similarity comparisons (KL / JS divergence).
* Designed experiments to evaluate robustness across sequence lengths, key-frame weighting, temporal ordering, and similarity metrics, leading to improved Recall@5 through optimized feature weighting strategies.
 Built end-to-end evaluation pipelines: KD-Tree ground-truth generation, sliding-window sequence construction, NetVLAD embedding extraction, and Recall@N benchmarking.
* Worked with researchers to explore new ideas for distribution-based sequence descriptors, temporal invariance, and connections between image-VPR and video-VPR models.

<h2>🛠️Research Intern</h2>  <img src="https://somikdhar729.github.io/images/FOCAS_lab_logo.png" alt="Drawing" width="150" height="150" align="right"/>
<i> Feb'21 - June'21 </i> <br>
<i><a href = "https://www.focaslab.com/" target="_blank" rel="noopener noreferrer" class="Project"> Formal Control and Autonomous Systems(FOCAS) Lab </a> </i><br>
<i><a href = "https://cps.iisc.ac.in/" target="_blank" rel="noopener noreferrer" class="Project">Robert-Bosch Centre for Cyber-Physical Systems (RBCCPS), Indian Institute of Science (IISc), Bangalore</a> </i> <br>

**Supervisor**: <a href = "https://www.pushpakjagtap.com/" target="_blank" rel="noopener noreferrer" class = "Project">Dr. Pushpak Jagtap, IISc, Bangalore <br></a>

* Led the setup and calibration of PhaseSpace Motion Capture System and developed ROS support for integrating the system with Turtlebot3 robots <br>
* Deployed Turtlebot3 robots with differential and mecanum drive configurations and utilized motion capture for accurate robot position tracking and real-time control adjustments <br>
* Implemented a Control Lyapunov Function (CLF) based controller in Python to guide unicycle modeled agents (robots) to desired poses <br>
* Implemented a barrier certificate-based collision avoidance algorithm for multi-agent systems using ROS(Python) <br>
* Achieved a 30cm safety radius in a 6m x 5m arena <br>

<a href = "https://somikdhar729.github.io/images/2022-05-09-172158.webm" target="_blank" rel="noopener noreferrer" class = "Project1">(Video 1)
<a href = "https://somikdhar729.github.io/images/2022-05-09-172334.webm" target="_blank" rel="noopener noreferrer" class = "Project1">(Video 2)


  

<h2> 🛠️Research Intern</h2> <img src="https://somikdhar729.github.io/images/IISc-Ril.jpg" alt="Drawing" width="150" height="150" align="right"/>
<i>  Jul'21 – Dec'21</i><br>
<a href = "https://cpdm.iisc.ac.in/ril/" target="_blank" rel="noopener noreferrer" class = "Project"> Robotics Innovations Lab(RIL), Indian Institute of Science, Bangalore <a> <br>


  
**Supervisor**: Dr. Abhra Roy Chowdhury, Indian Institute of Science<br>
* Built an autonomous differential-drive rover using DC motors, encoders, a microcontroller, and a forklift-style mechanism for object manipulation.
* Developed MATLAB-based models and control programs for autonomous navigation, including:
  * Characterizing motor response through PWM speed sweeps and data analysis
  * Implementing differential-drive kinematics for locomotion and arm control
  * Deriving and simulating kinematic and dynamic models for open-loop motion control
  * Designing and tuning a PID controller with encoder feedback for accurate position and heading control
* Added a webcam and localization algorithms to estimate rover position and enable vision-guided navigation.
* Integrated motion control, perception, and planning to perform high-level arena navigation and object manipulation tasks.
* Enhanced autonomy with line-following and obstacle-avoidance behaviors.
* Demonstrated strong skills in mechatronics, robotics modeling, control theory, computer vision, and autonomous decision-making.
  
(<a href = "https://somikdhar729.github.io/pdfs/MOBILE_ROBOT_Report.pdf" target="_blank" rel="noopener noreferrer" class = "Project1"><i>Project Report</i>)
(<a href = "https://www.youtube.com/watch?v=Hgscy7m2fI4" target="_black" rel="noopener noreferrer class" class="Project1"><i>Project Video</i></a>)
<!-- (<a href = "https://drive.google.com/file/d/18dZj0hBq_IXiXOePiThwjJaM5EECRZ0Z/view" target="_blank" rel="noopener noreferrer" class = "Project1"><i>Project Video</i>) -->

 
### Data Science Intern <img src="https://somikdhar729.github.io/images/m76-analytics.jpg" alt="Drawing" width="100" height="100" align="right"/>
<a href = "https://www.m76analytics.com/" target="_blank" rel="noopener noreferrer" class = "Project"> M76 Analytics, Mumbai </a>
<i> Aug'20 – Oct'20</i> <br>
<i>Supervisors: Jai Mrug, Srikanth Atkuri</i><br>
* Developed automated data processing functions in Python to clean and preprocess real-time industry data <br>
* Enabled more efficient analysis by engineering the data into structured formats by 25% <br>
* Built scripts for tasks including data formatting, handling missing values, outlier detection, feature encoding, and normalization<br>
* Deployed data pipeline at the backend of the organization's decision support system "MEGO"<br>
* Demonstrated skills in Python programming, data manipulation, pipeline development, and integration with business systems 





