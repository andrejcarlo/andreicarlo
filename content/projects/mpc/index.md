---
description: First Project
layout: "simple"
title: "A model predictive control approach for trajectory tracking of quadrotors" 
---

{{< figure src="/projects/mpc/results.jpg" alt="mpc quadrotor results" >}}


Our paper presents a model predictive control (MPC) approach for trajectory tracking of quadrotors, where a mathematical model of the quadrotor is developed with consideration of aerodynamic moment and drag to improve the simulation’s real-world accuracy. The simulation results demonstrate the quadrotor’s ability to track trajectories and avoid disturbances while satisfying state and control input constraints with satisfactory tracking error. The implementation of MPC with terminal constraints and penalties is successful, and we have proven the recursive local asymptotic stability of our MPC controller for trajectory tracking. Additionally, we have validated all assumptions and demonstrated stability through a confirmation of Lyapunov decrease and disturbance rejection a-posteriori.

For future work, we’d like to study non-linear adaptive MPC for tracking trajectories as presented in [9], to be able to perform highly agile maneuvers, which are not possible under the linearisation assumptions proposed in this paper. Moreover, another interesting study is the use of quaternion-based quadrotor [10] over euler based tracking. This can result in better tracking errors and less computational effort.

{{< button href="/projects/mpc/mpc_papuc_tang_final.pdf" target="_self" >}}
Download PDF
{{< /button >}}