---
description: Design of a drone swarm to measure the wind field and temperature stratification in a wind farm
# layout: "simple"
summary: "The goal of this project is to outline the sub-system design of the local sensing system, to satisfy the mission need statement: measure the atmospheric conditions with full three-dimensional coverage of a wind farm to optimize its operational performance and control."
title: "Design of a drone swarm to measure the wind field and temperature stratification in a wind farm"
---

<!-- {{< lead >}}
Bachelor's thesis, supervisor: Dr. Ir. Dries Allaerts 
{{< /lead >}} -->

{{< figure src="/projects/dse/cover-min.png" alt="Swarm of drones performing in a wind farm" >}}


The goal of this project is to outline the sub-system design of the local sensing system, to satisfy the mission need statement: **measure the atmospheric conditions with full three-dimensional coverage of a wind farm to optimize its operational performance and control**. This statement is derived from the need to improve the control and performance of wind farms through more informed processes and decisions, a task that meteorological masts would usually take on. However, the providable coverage is very low in comparison to the one a UAV based system could provide. UAVs have the potential to significantly increase the measure- ment coverage around an entire wind farm and in turn return to the user more valuable data.

To approach the finding of a solution to this problem, the project was divided into four: planning, concept definition, concept exploration and detailed design. From the first two phases came unique concepts exploring remote and local sensing options, combined with a range of UAV types includ- ing hybrid, fixed-wing and rotor. Through a detailed trade-off process and sensitivity analysis, the agreed upon final solution came to be a local sensing concept that makes use of many hybrid drones. In the fourth and final phase, where we now find ourselves, the detailed concept is un- packed and designed into a marketable system that is capable of satisfying the underlying MNS. In this stage the design was split into three design groups: UAV design, ground station design, swarm design.

The UAV department decided on an off-the-shelf UAV to ensure sufficient resources could be allocated to the design of the autonomous operations of the system. The final choice came to be the DeltaQuad Pro UAV, as this gives good endurance and ability to fly in windy conditions while being able to carry the chosen sensors: Trisonica mini (from Anemoment) for the wind speed and FST600-202 4-20mA PT100 (from Hunan FirstRate) for the temperature. These were selected for their compliance with the required accuracy and weight. The hybrid configuration is useful here as it allows the UAVs to take-off and land vertically whilst having efficient flight when measuring data.

The swarm department identified optimal flight routes with the chosen UAV, this allows the cal- culation of optimal number of ground stations and their placement. This was chosen to be a preset zig-zag path optimized for ground station positioning, later combined with a collision avoidance algorithm, making use of Rapidly-exploring Random Trees. This also allows the estimation of the spatial and temporal resolutions of 300 metres and 42 minutes respectively.

The ground station department worked to facilitate the autonomous operations of the system, to allow the UAVs to charge regularly and take shelter in non-operable conditions. To combat this, containers are designed to be constructed on the nacelle of the turbines (4 for charging the batter- ies and 17 for storage for a 100 [km2]), providing covered space for the UAVs to charge and be stored. Inside of these containers a robotic arm is placed, capable of withdrawing empty batteries and swapping them with charged batteries that are stored inside the container.

These design choices resulted in a system cost of 18.4M [€], with a power draw of 16.9 [kW]. The system was then verified against the system’s requirements and analyzed through the scope of a technical analysis and financial compliance review. With this insight, it became possible to determine full characteristics of the system as well as possible areas for further work.

{{< figure src="/projects/dse/DroneInGS-min.png" alt="Drone landing in a ground station" >}}

{{< button href="/projects/dse/dse_final_compressed.pdf" target="_self" >}}
Download PDF
{{< /button >}}