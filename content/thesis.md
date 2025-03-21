---
description: Interaction-aware Autonomous Drone Racing
layout: "simple"
# Optional: Add a menu entry directly via front matter
---
<!-- Centered Title Block -->
<div style="text-align: center; margin-top: 2rem; margin-bottom: 2rem;">
  <h1 style="margin-bottom: 0.5rem;">Interaction-aware Autonomous Drone Racing</h1>
  
  <!-- Authors block with equal spacing -->
  <div style="display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; font-size: 1.1rem;">
    <span>Andrei-Carlo Papuc</span>
    <span><a href=https://lasse-peters.net/>Lasse Peters</a></span>
    <span><a href=https://sihaosun.github.io//>Sihao Sun</a></span>
    <span><a href=https://autonomousrobots.nl/>Javier Alonso-Mora</a></span>
  </div>
  
  <p style="font-size: 1rem; color: #555; margin-top: 0.5rem;">
    Cognitive Robotics, TU Delft
  </p>
  <p style="display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; font-size: 1.1rem;">
    {{< button href="/thesis/" target="_self" >}}
    Thesis
    {{< /button >}}
    {{< button href="https://github.com/andrejcarlo/agile_multi_agent" target="_self" >}}
     {{< icon "github" >}} <span style="margin-left: 4px;">Code</span>
    {{< /button >}}
  </p>
</div>

<hr style="width: 60%; margin: 2rem auto;">

<!-- Embedded Video -->
<div style="text-align: center; margin: 2rem 0;">
  {{< youtube 7u5bAj3fGQQ >}}
</div>

<!-- Description -->
<div style="max-width: 800px; margin: 0 auto; text-align: justify;">
  <h2 style="text-align: center;">Abstract</h2>
  <p>
    This thesis explores interaction-aware decision-making strategies in autonomous drone racing. 
    We investigate how multi-agent game-theoretic approaches can enhance competitive performance in high-speed racing environments.
  </p>

  <p>
    Autonomous drone racing presents a unique challenge that requires both high-speed motion planning and strategic decision-making in a multi-agent setting. Prior work has primarily relied on model predictive control (MPC) methods that treat opponents as dynamic obstacles, limiting their ability to model strategic interactions. In this work, we formulate drone racing as a dynamic game and introduce game-theoretic planning methods that compute open-loop Nash equilibria, incorporate blocking strategies, and accelerate decision-making using learning-based techniques. These methods explicitly model opponent behavior, allowing drones to anticipate and react strategically in high-speed racing scenarios. To assess the effectiveness of our approach, we conduct a large-scale head-to-head tournament against MPC-based planners, demonstrating that interaction-aware planning enables more effective overtaking and defensive strategies, leading to a higher wining rate. However, computational delays in high-speed decision-making can limit performance, highlighting the need for efficient techniques that balance real-time feasibility with strategic adaptability. Our results show that learning-based acceleration significantly improves decision-making speed while preserving competitive advantages. Finally, high-fidelity simulations and real-world drone racing experiments validate the feasibility of these methods, confirming their ability to generate reliable and competitive strategies under practical racing conditions.
  </p>
</div>