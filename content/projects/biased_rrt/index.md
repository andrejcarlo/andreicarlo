---
description: First Project
layout: "simple"
title: "Obstacle driven RRT implementation for quad‐rotor motion planning"
---

{{< figure src="/projects/biased_rrt/cover.png" alt="biased RRT pipeline" >}}


This paper presents the development of a version of RRT* optimized for indoor environments, called biased RRT*. The numerical analysis results showed promising benefits, especially for quick path generation in case of a large number of obstacles or small holes. In practice, this could be useful for crowded, dynamic indoor environments, allowing for quick recomputation of the global path in case of a change in environment, newly detected obstacles, or even continuous computation of the global path. Additionally, it is shown that RRT could be combined with a local path planner like MPC to create a full offline-online integrated motion planner for quad-rotors in 3D environments.

{{< figure src="/projects/biased_rrt/analysis_results.png" alt="biased RRT analysis results" >}}

{{< button href="/projects/biased_rrt/pdm_final.pdf" target="_self" >}}
Download PDF
{{< /button >}}