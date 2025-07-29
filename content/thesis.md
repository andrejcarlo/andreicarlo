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
    {{< button href="/poster_iaadr.pdf" target="_self" >}}
     Poster
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

<div style="max-width: 800px; margin: 0 auto; text-align: left;">
  <h2 style="text-align: center;">References</h2>
  <p>[1] Tamer Başar and Geert Jan Olsder. Dynamic Noncooperative Game Theory, 2nd Edition. Society for Industrial and Applied Mathematics, 1998. DOI: 10.1137/1.9781611971132. eprint: https://epubs.siam.org/doi/pdf/10.1137/1.9781611971132. URL: https://epubs.siam.org/doi/abs/10.1137/1.9781611971132.</p>
  <p>[2] Leonard Bauersfeld and Davide Scaramuzza. "Range, endurance, and optimal speed estimates for multicopters". In: IEEE Robotics and Automation Letters 7.2 (2022), pp. 2953-2960.</p>
  <p>[3] Johannes Betz et al. "Autonomous vehicles on the edge: A survey on autonomous vehicle racing". In: IEEE Open Journal of Intelligent Transportation Systems 3 (2022), pp. 458-488.</p>
  <p>[4] Andrew Cinar and Forrest Laine. Does bilevel optimization result in more competitive racing behavior? 2025. arXiv: 2402.09548 [cs.GT]. URL: https://arxiv.org/abs/2402.09548.</p>
  <p>[5] Benjamin Evans, Herman A Engelbrecht, and Hendrik W Jordaan. "Learning the subsystem of local planning for autonomous racing". In: 2021 20th International Conference on Advanced Robotics (ICAR). IEEE. 2021, pp. 601-606.</p>
  <p>[6] Jaime F Fisac et al. "Hierarchical game-theoretic planning for autonomous vehicles". In: 2019 International conference on robotics and automation (ICRA). IEEE. 2019, pp. 9590-9596.</p>
  <p>[7] Philipp Foehn et al. "Agilicious: Open-source and open-hardware agile quadrotor for vision-based flight". In: Science Robotics 7.67 (June 2022). ISSN: 2470-9476. DOI: 10.1126/scirobotics.ab16259. URL: http://dx.doi.org/10.1126/scirobotics.abl6259.</p>
  <p>[8] David Fridovich-Keil. Smooth Game Theory. 2024. URL: https://clearoboticslab.github.io/documents/smooth_game_theory.pdf.</p>
  <p>[9] David Fridovich-Keil et al. "Efficient iterative linear-quadratic approximations for nonlinear multiplayer general-sum differential games". In: 2020 IEEE international conference on robotics and automation (ICRA). IEEE. 2020, pp. 1475-1481.</p>
  <p>[10] Fadri Furrer et al. "Robot Operating System (ROS): The Complete Reference (Volume 1)". In: ed. by Anis Koubaa. Cham: Springer International Publishing, 2016. Chap. RotorS-A Modular Gazebo MAV Simulator Framework, pp. 595-625. ISBN: 978-3-319-26054-9. DOI: 10.1007/978-3-319-26054-9_23. URL: http://dx.doi.org/10.1007/978-3-319-26054-9_23.</p>
  <p>[11] Drew Hanover et al. "Autonomous Drone Racing: A Survey". In: IEEE Transactions on Robotics 40 (2024), pp. 3044-3067. DOI: 10.1109/TRO.2024.3400838.</p>
  <p>[12] Suiyi He, Jun Zeng, and Koushil Sreenath. "Autonomous racing with multiple vehicles using a parallelized optimization with safety guarantee using control barrier functions". In: 2022 International conference on robotics and automation (ICRA). IEEE. 2022, pp. 3444-3451.</p>
  <p>[13] Haimin Hu et al. "Who Plays First? Optimizing the Order of Play in Stackelberg Games with Many Robots". In: Proceedings of Robotics: Science and Systems. Delft, Netherlands, 2024. DOI: 10.15607/RSS.2024.XX.116.</p>
  <p>[14] Yixuan Jia, Maulik Bhatt, and Negar Mehr. "Rapid: Autonomous multi-agent racing using constrained potential dynamic games". In: 2023 European Control Conference (ECC). IEEE. 2023, pp. 1-8.</p>
  <p>[15] Dvij Kalaria et al. "Local nmpc on global optimised path for autonomous racing". In: arXiv preprint arXiv:2109.07105 (2021).</p>
  <p>[16] Yu Kang et al. "Autonomous multi-drone racing method based on deep reinforcement learning". In: Science China Information Sciences 67.8 (2024), p. 180203.</p>
  <p>[17] Talha Kavuncu, Ayberk Yaraneri, and Negar Mehr. "Potential ilqr: A potential-minimizing controller for planning multi-agent interactive trajectories". In: arXiv preprint arXiv:2107.04926 (2021).</p>
  <p>[18] Pravesh Koirala and Forrest Laine. "Monte carlo optimization for solving multilevel stackelberg games". In: arXiv preprint arXiv:2312.03282 (2023).</p>
  <p>[19] Forrest Laine et al. "The computation of approximate generalized feedback nash equilibria". In: SIAM Journal on Optimization 33.1 (2023), pp. 294-318.</p>
  <p>[20] Simon Le Cleac'h, Mac Schwager, and Zachary Manchester. "Algames: a fast augmented lagrangian solver for constrained dynamic games". In: Autonomous Robots 46.1 (2022), pp. 201-215.</p>
  <p>[21] Jingqi Li et al. "The Computation of Approximate Feedback Stackelberg Equilibria in Multiplayer Nonlinear Constrained Dynamic Games". In: SIAM Journal on Optimization 34.4 (2024), pp. 3723-3749.</p>
  <p>[22] Alexander Liniger, Alexander Domahidi, and Manfred Morari. "Optimization-based autonomous racing of 1: 43 scale RC cars". In: Optimal Control Applications and Methods 36.5 (2015), pp. 628-647.</p>
  <p>[23] Alexander Liniger and John Lygeros. "A noncooperative game approach to autonomous racing". In: IEEE Transactions on Control Systems Technology 28.3 (2019), pp. 884-897.</p>
  <p>[24] Xinjie Liu, Lasse Peters, and Javier Alonso-Mora. "Learning to Play Trajectory Games Against Opponents With Unknown Objectives". In: IEEE Robotics and Automation Letters 8.7 (2023), pp. 4139-4146. DOI: 10.1109/LRA.2023.3280809.</p>
  <p>[25] Patrick Kofod Mogensen and Asbjørn Nilsen Riseth. "Optim: A mathematical optimization package for Julia". In: Journal of Open Source Software 3.24 (2018), p. 615. DOI: 10.21105/joss.00615.</p>
  <p>[26] L. Peters et al. "Learning Mixed Strategies in Trajectory Games". In: Proceedings Robotics: Science and System XVIII. Ed. by Kris Hauser, Dylan Shell, and Shoudong Huang. Robotics: Science and Systems. Robotics Science and Systems (RSS), 2022. DOI: 10.15607/RSS.2022.XVIII.051.</p>
  <p>[27] Angel Romero et al. "Model predictive contouring control for time-optimal quadrotor flight". In: IEEE Transactions on Robotics 38.6 (2022), pp. 3340-3356.</p>
  <p>[28] Matthias Rowold et al. "Efficient spatiotemporal graph search for local trajectory planning on oval race tracks". In: Actuators. Vol. 11. 11. MDPI. 2022, . 319.</p>
  <p>[29] Matthias Rowold et al. Open-Loop and Feedback Nash Trajectories for Competitive Racing with iLQGames. 2024. arXiv: 2402.01918 [cs.RO]. URL: https://arxiv.org/abs/2402.01918.</p>
  <p>[30] Maria Luisa Scarpa and Thulasi Mylvaganam. "Open-loop and feedback LQ potential differential games for Multi-Agent Systems". In: 2023 62nd IEEE Conference on Decision and Control (CDC). IEEE. 2023, pp. 6283-6288.</p>
  <p>[31] Yunlong Song et al. "Autonomous drone racing with deep reinforcement learning". In: 2021 IEEE International Conference on Intelligent Robots and Systems (IROS). IEEE. 2021, pp. 1205-1212.</p>
  <p>[32] Riccardo Spica et al. "A real-time game theoretic planner for autonomous two-player drone racing". In: IEEE Transactions on Robotics 36.5 (2020), pp. 1389-1403.</p>
  <p>[33] Rishabh Saumil Thakkar et al. "Hierarchical control for cooperative teams in competitive autonomous racing". In: IEEE Transactions on Intelligent Vehicles 9.5 (2024), pp. 4845-4860.</p>
  <p>[34] Rishabh Saumil Thakkar et al. "Hierarchical control for head-to-head autonomous racing". In: Field Robotics 4 (2024), pp. 46-69.</p>
  <p>[35] José L Vázquez et al. "Optimization-based hierarchical motion planning for autonomous racing". In: 2020 IEEE/RSJ international conference on intelligent robots and systems (IROS). IEEE. 2020, pp. 2397-2403.</p>
  <p>[36] Andreas Wächter and Lorenz T Biegler. "On the implementation of an interior-point filter line-search algorithm for large-scale nonlinear programming". In: Mathematical programming 106 (2006), pp. 25-57.</p>
  <p>[37] Zijian Wang, Tim Taubner, and Mac Schwager. "Multi-agent sensitivity enhanced iterative best response: A real-time game theoretic planner for drone racing in 3D environments". In: Robotics and Autonomous Systems 125 (2020), p. 103410.</p>
  <p>[38] Peter Werner et al. "Dynamic multi-team racing: Competitive driving on 1/10-th scale vehicles via learning in simulation". In: 7th Annual Conference on Robot Learning. 2023.</p>
  <p>[39] Grady Williams et al. "Autonomous racing with autorally vehicles and differential games". In: arXiv preprint arXiv:1707.04540 (2017).</p>
  <p>[40] Jiaxu Xing et al. "Bootstrapping reinforcement learning with imitation for vision-based agile flight". In: arXiv preprint arXiv:2403.12203 (2024).</p>
  <p>[41] Alessandro Zanardi et al. Game Theoretical Motion Planning. Tutorial ICRA 2021. ETH Zurich, 2021. DOI: 10.3929/ethz-b-000507914.</p>
  <p>[42] Edward L. Zhu and Francesco Borrelli. "A Sequential Quadratic Programming Approach to the Solution of Open-Loop Generalized Nash Equilibria". In: 2023 IEEE International Conference on Robotics and Automation (ICRA). 2023, pp. 3211-3217. DOI: 10.1109/ICRA48891.2023.10160799.</p>
  <p>[43] Edward L. Zhu and Francesco Borrelli. A Sequential Quadratic Programming Approach to the Solution of Open-Loop Generalized Nash Equilibria for Autonomous Racing. 2024. arXiv: 2404.00186 [cs.RO]. URL: https://arxiv.org/abs/2404.00186.</p>
</div>