---
description: First Project
layout: "simple"
summary: "Smart Rotor Models (SRM) allow for modification of the wind turbine's aerodynamic properties using an actuated flap to alleviate the effects of sudden peak loads caused by wind gusts. Wind tunnel experiments conducted with the help of Robotic Particle Image Velocimetry (RPIV) measure the flow surrounding such models."
title: "Robotic particle image velocimetry for position reconstruction of a smart rotor model"
---

{{< katex >}}

<center>
    <div style="display:flex; ">
         <div style="flex:1;padding-right:0px;">
              <img src="/projects/rpiv/test_setup.png" width="400"/>
         </div>
         <div style="flex:1;padding-left:0px; ">
            <div style="flex:1;padding-bottom:0px;">
                <img src="/projects/rpiv/case_1_results.png" width="400"/>
            </div>
            <div style="flex:1;padding-top:0px;">
                <img src="/projects/rpiv/results.gif" width="350"/>
            </div>
        </div>
    </div>
</center>

Smart Rotor Models (SRM) allow for modification of the wind turbine's aerodynamic properties using an actuated flap to alleviate the effects of sudden peak loads caused by wind gusts. Wind tunnel experiments conducted with the help of Robotic Particle Image Velocimetry (RPIV) measure the flow surrounding such models.

Thus, a need emerges for the measurements from the RPIV to be transformed so the positions of the SRM may be determined at all times to facilitate the progress of the experiment. 

With the help of structural markers in a grid, this was done by identifying the locations of the various data points, removing outliers, and fitting data points over the grid with the help of translation algorithms. Once the translation distances were found, the angles of attack were computed. The results were made more accurate by dividing the airfoil into the main body and flap with an xy-plane passing perpendicularly through the surface of the airfoil, allowing for the computation of flap deflection. Iteration of the final step allowed for the generation of the results in 3 cases: the first in which the main body and flap were fixed; the second wherein the airfoil had a pitching motion; and the third where the main body had a pitching motion while the flap deflected. 

The outlined method produced graphs representing the motion of the airfoil over time. Given that the sinusoidal pitching motion was known to have a 4\\(\degree\\) amplitude and a 0.4 Hz frequency, the chosen method provided amplitude and frequency readings of 3.97\\(\degree\\) and 0.39 Hz, proving to be an appropriate form of computation.
