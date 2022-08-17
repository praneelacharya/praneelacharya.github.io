---
title: 'NACA 4 digit airfoil with maximum CL/CD'
# date: 2012-08-14
permalink: /posts/2022/05/Aerodynamics/
# tags:
#   - cool posts
#   - category1
#   - category2
---

In this project, we explore the different four-digit NACA airfoils. Four-digit NACA airfoil is described by three parameters: while first digit describes the maximum chamber as percentage of the chord, second digit describes of maximum camber the airfoil leading edge in tenths of the chord, and the last two digits describing maximum thickness as percent of the chord. Thus, we change those parameters and find the best NACA airfoil based on maximum CL/CD.

Prameters:
------
1. Freestream velocity: 20 m/s  (Based upon analysis of fixed wing UAV including Albatross, Slybird and others).
2. Reynolds number: 1.4e6 (for AVL)
3. Viscous mode: On (For AVL)
4. Angle of attack (AoA): 0 degrees (for AVL)


Steps:
------
1. MATLAB Scripts that calls AVL, generates the airfoil, run the analysis in 0 AoA and saves the airfoil and coeffiecnt of lieft and drag in the text file.
2. MATLAB Script that looks into all saved text files and short out the airfoils with following properties:
    1. Maximum coeffiecnt of lift.
    2. Maximum coefficent of drag.
    3. Maximum ratio of coffiecent of lift to drag.

Results:
------
1. MATLAB Scripts that calls AVL, generates the airfoil, run the analysis in 0 AoA and saves the airfoil and coeffiecnt of lieft and drag in the text file.
2. MATLAB Script that looks into all saved text files and short out the airfoils with following properties:
    1. Maximum coeffiecnt of lift.
    2. Maximum coefficent of drag.
    3. Maximum ratio of coffiecent of lift to drag.


<div class= embed-responsive embed-responsive-16by9>

<iframe width="560" height="315" src="https://www.youtube.com/embed/hbPxzm71A9U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</div>


<!-- Headings are cool
======

You can have many headings
====== -->

Introduction
------
Lift and drag are defined by following equation: <br/>
$ L = 0.5 \rho V^2 S C_L $
<!-- D=0.5ρV^2 SC_D -->
L, D: Lift, Drag
ρ : Freestream density
V : Freestream velocity
S: Surface area
C_L  , C_D  : Coefficient of lift, coefficient of drag
Thus, to increase lift (L) there are following options:
	Increase the velocity will lead to increase in lift but at the expense of increase drag.
	Increase in surface area will lead to increase in lift but at the expense of increase drag.
	Increase in coefficient of lift CL on lead to increase in lift and does not affect drag.
	Max CL/CD will increase lift with decrease in drag with all parameters (ρ,V,S) fixed. 
Thus, max CL/CD is desired. 

<!-- $$ \nabla_\boldsymbol{x} J(\boldsymbol{x}) $$ -->



<!-- To add an image we do the following ![ Description of the image]( Link of the image ) -->


![image-title-here](blog-Aerodynamics-maxCL.png){:class="img-responsive"}