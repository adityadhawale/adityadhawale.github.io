---
layout: page
title: Aditya N Dhawale
subtitle: Master of Science in Robotics, CMU
---

<img style="float: right; max-width:30%;" src="/img/facebook_dp.jpg">

I am a Master of Science student at [The Robotics Institute](https://www.ri.cmu.edu/), Carnegie Mellon University. 
I work with professor [Nathan Michael](https://nmichael.me/) at the [Resilient Intelligent Systems Lab (RISLab)](https://www.rislab.org/). 
I obtained my Bachelor of Technology (B.Tech) from the [Indian Institute of Technology, Guwahati](http://www.iitg.ac.in/) in 2016 with a major in Mechanical Engineering.

My primary research interest is high fidelity 3D perception, mapping and localization on autonomous systems. To this end, my current work in RISLab focuses on developing real-time solutions for Simultaneous Localization and Mapping (SLAM) in large scale unknown environments on embedded systems.

Email: <adityadhawale6@gmail.com> 

## Research

  **GMM-Fusion: Multi-Fidelity Dense SLAM with Gaussian Distributions**<br>
  **A. Dhawale**, K. Shaurya Shankar, N. Michael<br>
  <img style="float: left; padding:5px" src="/img/icd_1-min.gif" height="212" width="370">
  <img style="float: center; padding:5px" src="/img/icd_2.gif" height="212" width="370">

  <font size="2">In this project, we are proposing a framework to perform uncertainty aware SLAM on embedded platforms by using a Gaussian distributions as our map representation.  Our pipeline uses Gaussian distributions as structure primitives that support both high fidelity surface reconstruction and low fidelity structure reconstruction for robotic applications. We perform dense frame-to-model camera tracking and a global incremental Gaussian Mixture Model (GMM) mapping of the world. <br> </font>
  - - - -

  **Efficient Parametric Multi-Fidelity Surface Mapping**<br>
  **A. Dhawale**, N. Michael<br>
  <img style="float: left; padding:20px" src="/img/hgmm.gif" height="200" width="260">

  <font size="2">State-of-the-art dense mapping approaches cannot be deployed on SWaP constrained platforms because of their large memory and compute requirements. In this work, we presented an accurate, dense, and efficient approach to multi-fidelity 3D mapping using Gaussian distributions as volumetric primitives that supports both high fidelity dense surface reconstruction and lower fidelity environment representation for fundamental robotics applications.<br> </font>
  - - - -

  **Reactive Collision Avoidance Using Real-Time Local Gaussian Mixture Model Maps** [[pdf](https://ieeexplore.ieee.org/document/8593723), [video](http://www.youtube.com/watch?feature=player_embedded&v=3MyJdu3bKSQ)]<br>
  **A. Dhawale**, X. Yang, N. Michael<br>
  <img style="float: left; padding:20px" src="/img/gmm_avoid.gif" height="200" width="260">

  <font size="2">In unknown, cluttered environments, robots require online real-time mapping and collision checking in order to navigate robustly. In this project, we take a probabilistic approach to local mapping by representing the environment as a Gaussian Mixture Model (GMM) and leverage its geometric properties to enable efficient collision checking given a time-parameterized trajectory. In contrast to current discretization-based methods, a GMM preserves geometric coverage of the environment without losing representation accuracy with varying map resolutions.<br> </font>
  - - - -

  **Fast and Agile Vision-Based Flight with Teleoperation and Collision Avoidance on a Multirotor** [[pdf](https://link.springer.com/chapter/10.1007%2F978-3-030-33950-0_45), [video](https://www.youtube.com/watch?v=_-KmGhP0HTQ)]<br>
  A. E. Spitzer, X. Yang, J. W. Yao, **A. Dhawale**, K. Goel, M. Dabhi, M. Collins, C. Boirum, and N. Michael<br>

  <img style="float: left; padding:5px" src="/img/fast.gif" height="185" width="245">
  <img style="float: center; padding:5px" src="/img/coll_avoid_1.gif" height="185" width="245">
  <img style="float: right; padding:5px" src="/img/coll_avoid_2.gif" height="185" width="245">

  <font size="2">Here, we presented a multirotor architecture capable of aggressive autonomous flight and collision-free teleoperation in unstructured, GPS-denied environments. The proposed system enables aggressive and safe autonomous flight around clutter by integrating recent advancements in visual-inertial state estimation and teleoperation. Our system enables a non-expert operator to safely navigate a multirotor around obstacles at speeds of 10 m/s and achieve autonomous flights at speeds exceeding 12 m/s.<br> </font>
  - - - -
  
  **Fast Monte-Carlo Localization on Aerial Vehicles Using Approximate Continuous Belief Distributions** [[pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Dhawale_Fast_Monte-Carlo_Localization_CVPR_2018_paper.pdf), [video](https://www.youtube.com/watch?v=RzS2v32850E&t=2s)] <br>
  **A. Dhawale**, K. Shaurya Shankar, N. Michael<br>
  <img style="float: left; padding:20px" src="/img/gear.gif" height="200" width="260">

  <font size="2">In this project, we designed a framework to perform fast localization on SWaP constrained platforms enabled by the compressive capabilities of Gaussian Mixture Model representations of point cloud data. Given raw structural data from a depth sensor and pitch and roll estimates from an on-board attitude reference system, a multi-hypothesis particle filter localizes the vehicle by exploiting the likelihood of the data originating from the mixture model.<br> </font>
  - - - -
