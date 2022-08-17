---
title: 'NACA 4 digit airfoil with maximum CL/CD'
date: 2012-08-14
permalink: /posts/2022/05/Aerodynamics/
# tags:
#   - cool posts
#   - category1
#   - category2
---

In this project, we explore the different four-digit NACA airfoils. Four-digit NACA airfoil is described by three parameters: while first digit describes the maximum chamber as percentage of the chord, second digit describes of maximum camber the airfoil leading edge in tenths of the chord, and the last two digits describing maximum thickness as percent of the chord. Thus, we change those parameters and find the best NACA airfoil based on maximum CL/CD.

<!-- Headings are cool
======

You can have many headings
====== -->

Introduction
------
Lift and drag are defined by following equation: <br/>
L=0.5ρV^2 SC_L
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