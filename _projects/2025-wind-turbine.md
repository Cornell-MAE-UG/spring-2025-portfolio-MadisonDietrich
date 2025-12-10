---
layout: project
title: Wind Turbine
description: Designing and testing a wind turbine
technologies: [Autodesk Fusion, Matlab]
image: /assets/images/BladeCAD.png

---
For this project, my groupmates and I were asked to design small wind turbine blades with the objective of maximizing power extraction at a set angular velocity. We settled on our design by splitting the blade into 10 sections and finding the chord legth and pitch for each section that maximized the ratio of lift coefficient to drag coefficient. We also swept through angular velocities to determine the one that maximized power.

Once we had our blades designed and printed, we tested them in a wind tunnel. We wanted to generate three power curves to determine if the angular velocity we designed for was optimal and verify that the blades would not fracture. The results were that the maximum power was 0.049 W, 0.214 W, and 0.904 W for wind speeds of 3 m/s, 4.6 m/s, and 6.3 m/s, respectively.



<p align="center">
  <img src="{{ '/assets/images/BladeTesting.png' | relative_url }}" width="40%">
  <img src="{{ '/assets/images/PowerCurve.png' | relative_url }}" width="50%">
</p>


