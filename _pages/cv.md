---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version is available [here](/files/Resume.pdf).

Education
======
* B.S. in Computer Science, Carnegie Mellon University, 2021 – 2025

Experience
======
* 2025 – present: **Member of Technical Staff**, Skild AI, Pittsburgh, PA
  * Robot learning for general-purpose robotics.

* 2023 – 2025: **Research Assistant**, Robotics Institute, Carnegie Mellon University
  * Advised by Prof. Jiaoyang Li (ARCS Lab). Developed methods for improving the execution
    efficiency of multi-agent path finding plans under delays, without requiring replanning,
    via bidirectional temporal plan graphs. Implemented in C++ with simulation in Python;
    resulted in publications at AAAI 2024 and AAAI 2026.
  * Worked with Prof. Deepak Pathak on scaling reinforcement learning for dexterous
    manipulation and legged locomotion (Evolutionary Policy Optimization).

* 2022 – 2023: **Research Assistant**, AirLab, Robotics Institute, Carnegie Mellon University
  * Multi-drone reconstruction system, advised by Prof. Sebastian Scherer and Prof. Micah Corah.
  * Built the GPS backpack carried by ground experimenters using Raspberry Pi and ROS, with
    RTK for centimeter-level accuracy and Rajant mesh radio for multi-agent communication.
  * Developed a real-time health monitor for the full system in Python and C++.
  * Independent study on multi-drone coverage and submodular maximization.

Projects
======
* **Robot Juggling** — learning bimanual juggling with an anthropomorphic hand, via curriculum-based
  model-free RL and learning from demonstration trajectories extracted from video.
* **Sampling-Based Motion Planning with Dynamics** (2023) — re-implementation of the GUided Sampling
  Tree (GUST) algorithm in C++ for kinodynamic planning; ~3× faster than RRT on our most complex map.
* **Multi-Robot Multi-Target Coverage** — continuous greedy algorithm for maximizing robot coverage
  of multiple targets.
* **The Cube** (2022–2023) — on-campus app for real-time anonymous classroom chat. Led the project
  concept; front-end in React and JavaScript, plus API design.
* **Mobile Robot System Project** (2022) — autonomous mobile forklift in MATLAB that locates, lifts,
  and transports targets.
* **MAGC Map** — non-linear mind-mapping tool. Third place, HackCMU 2021. Front-end in HTML and JavaScript.

Skills
======
* **Languages:** C/C++, Python, JavaScript, Swift, MATLAB, SML
* **Robotics & ML:** ROS, reinforcement learning, motion planning, multi-agent path finding, simulation
* **Web:** React, JavaScript, API design

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Portfolio
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
