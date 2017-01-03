---
layout: project
title: Collision Avoidance Simulation Tool
date: December 20, 2016
box: http://img.youtube.com/vi/f88BVyyIess/0.jpg
image:
---

## Overview

##### Group Project was completed for EECS 395: Compuational Geometry.

##### Group Members: Elton Cheng, Mario Sebasco, Chainatee Tanakulrungson

The goal of this project was to create a tool that would simulate collision avoidance in a system of moving robots. The algorithms and logic behind this project is based off the research paper [Generalized Reciprocal Collision Avoidance] by Daman Bareiss and Jur van den Berg.

The system we describe in this tool consists of only one active robot and multiple passive drive robots. What this means is only the active robot will be responsible for avoiding collision; the passive robots will focus on moving towards their destination.

The collision avoidance algorithm that we implement in this tool is similar to the velocity obstacles that are described in the paper. The active robot will continously search its perimeter for any local robots. If a robot is detected, the active robot will determine whether or not its current velocity will cause a collision in the future within 5 seconds. If a future collision is detected, a change to the velocity input will be applied such that a collision will not happen.

Below are several videos that show the following scenarios implemented by the tool: 1 active and 1 passive, 1 active and 2 passive, and 1 active and 3 passive.

In the future, we would like to implement further fine tuning of the algorithm, more variety in the equations of motion of the robots, and being able to insert any map of the world that the robots will be able to navigate through.

{: .center}
[![2 Robots - V1](http://img.youtube.com/vi/FTm0ED6ZIZA/0.jpg)](https://www.youtube.com/watch?v=FTm0ED6ZIZA "2 Robots - V1"){:target="_blank"}
[![2 Robots - V2](http://img.youtube.com/vi/il0v5pRQLqM/0.jpg)](https://www.youtube.com/watch?v=il0v5pRQLqM "2 Robots - V2"){:target="_blank"}

{: .center}
[![3 Robots](http://img.youtube.com/vi/11ZxD_-BOU0/0.jpg)](https://www.youtube.com/watch?v=11ZxD_-BOU0 "3 Robots"){:target="_blank"}
[![4 Robots](http://img.youtube.com/vi/f88BVyyIess/0.jpg)](https://www.youtube.com/watch?v=f88BVyyIess "4 Robots"){:target="_blank"}


[Generalized Reciprocal Collision Avoidance]:<http://arl.cs.utah.edu/pubs/IJRR2015.pdf>


