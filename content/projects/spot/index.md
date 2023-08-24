---
description: First Project
layout: "simple"
title: "Autonomous legged robot solution for efficient lost item retrieval" 
---

{{< youtube aRhWC4B2W3Q >}}

One of the specific investigations of [TNO](https://www.tno.nl/en/) concerns the applicability of Boston Dynamics’ Spot robot for domestic applications, i.e., applying SPOT as a robotic assistance dog.

The team had a clear objective: to make the most of Spot by using it to locate lost items efficiently. To achieve this goal, Spot needed the ability to detect objects and deliver them accurately to the right people. After carefully analyzing operational scenarios and requirements, we established a functional hierarchy. This meant Spot had to recognize items like apples, balls, and screwdrivers, as well as identify people based on their shirt colors. To accomplish this, Spot required knowledge of its surroundings, the locations of people, and where objects were situated. To pick up and deliver objects, we needed a navigation system. Throughout this process, our priority was to ensure that Spot's intentions were transparent and its actions were safe.

We employed YOLOv5 for detecting humans and objects. While this model could identify humans, apples, and balls, it struggled with screwdrivers. To address this, we expanded the YOLO model using transfer learning, training it on a dataset of meticulously annotated images. Creating a 3D map of objects involved combining the centers of bounding boxes with corresponding depth camera points and converting these points into a global mapping.

Navigation in open spaces was managed using a 2D occupancy grid. Due to potential imprecisions and drift in Spot's odometry, we employed the Rao-Blackwellized particle filter, gmapping, for simultaneous localization and mapping. This involved transforming depth camera images into point clouds and laser scans. Navigating within the mapped environment was achieved through the move base package, which seamlessly integrated global and local planning through a finite state machine. The planner efficiently explored by identifying points with the greatest distance separation.

{{< figure src="/projects/spot/spot_slam.png" alt="spot robot performing SLAM" >}}

The decision handler, implemented as a finite state machine (FSM), played a pivotal role in coordinating various functions and overseeing Spot's operations. The FSM progressed sequentially, with specific action servers activating during distinct states. Notably, the 'scan' and 'explore' actions were particularly significant. The decision handler managed initialization, task selection, and submodule states. This complex orchestration was presented through a user-friendly graphical interface.

While each component performed well individually in simulations and real-world tests, the integration of sub-modules resulted in performance that fell short of our expectations. This decline in perception, planning, and navigation effectiveness seemed to be linked to computational limitations during simultaneous operation. Given additional time and focused effort, it's likely these challenges could have been addressed.

{{< button href="/projects/spot/spot.pdf" target="_self" >}}
Read More
{{< /button >}}
