---
layout: project
title: Wind Turbine
description: Designing and testing a wind turbine
technologies: [Autodesk Fusion, Matlab]
image: /assets/images/BladeCAD.png

---
To further our understanding of fluid mechanics and wind turbines, my groupmates and I were asked to design small wind turbine blades with the objective of maximizing power extraction at a set angular velocity. We settled on our design by splitting the blade into 10 sections and finding the chord legth and pitch for each section that maximized the ratio of lift coefficient to drag coefficient. We also swept through angular velocities to determine the one that maximized power, which ended up being 800 RPM. I then made a CAD model of the design, which we had 3D printed.

Once we had our blades designed and printed, we tested them in a wind tunnel. We wanted to generate three power curves to determine if the angular velocity we designed for was optimal and verify that the blades would not fracture. For each power curve, we set the wind tunnel to a constant wind speed and slowly increased the voltage to a torque brake, which lowered the angular velocity of the turbine. The results were that the maximum power was 0.049 W, 0.214 W, and 0.904 W for wind speeds of 3 m/s, 4.6 m/s, and 6.3 m/s, respectively. For the 4.6 m/s velocity, which is the wind speed we designed for, the maximum power occured at 750 RPM, which is very similar to the 800 RPM we were expecting. The main difference between the theoretical and experimental power curves was that the experimental power (0.214 W) was much lower than the theoretical one (2.666 W). This was expected for several reasons: we did not account for tip losses or friction when designing the blades, the blades had more surface roughness than expected, and the wind tunnel we tested in was small relative to the length of the blades.

Despite this, our wind turbine was successful at generating power, and we learned more about blade design and testing.



<p align="center">
  <img src="{{ '/assets/images/BladeTesting.png' | relative_url }}" width="40%">
  <img src="{{ '/assets/images/PowerCurve.png' | relative_url }}" width="50%">
</p>


