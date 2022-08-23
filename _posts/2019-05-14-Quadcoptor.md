---
title: 'PID control design, simulation and implementation for Parrot ARDrone'
# date: 2012-08-14
permalink: /posts/2019/05/Quadcoptor/
tags:
  - MATLAB
  - Parrot ARDrone
---

This project was carried out as a class project for the Robotics class (ME 541) at South Dakota State University. The goal was to develop a PID controller and tune it in MATLAB such that the quadcopter follows the desired trajectory. 

The controller was based on the control law purposed by Tasy and his team (Tsay, Tain-Sou. "Guidance and control laws for quadrotor UAV." WSEAS Trans. on Systems and Control 9 (2014): 606-613). 

Once the controller was tuned in MATLAB, the gain values were provided to the existing interface that would write those gain values to the parrot ARDrone. 

Screenshot of MATLAB/Simulink UAV model
<br/><img src='/images/blog_images/Quad_matlab_model.png'>

Tuned gain trajectory following
<br/><img src='/images/blog_images/Quad_sim_results.png'>

Gain implemented in Parrot AR Drone. 
<br/><img src='/images/blog_images/Quad_result1.png'>
<br/><img src='/images/blog_images/Quad_result2.png'>


Screenshot of MATLAB/Simulink UAV model
<br/><img src='/images/blog-Quad_matlab_model.png'>

Tuned gain trajectory following
<br/><img src='/images/blog-Quad_sim_results.png'>

Gain implemented in Parrot AR Drone. 
<br/><img src='/images/blog-Quad_result1.png'>
<br/><img src='/images/blog-Quad_result2.png'>

