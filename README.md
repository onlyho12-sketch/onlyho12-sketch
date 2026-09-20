<div align="center">

<br>

### Hyeonho Shin

**Robotics · AI · Digital Twin**

<br>

*Teaching robots to see, decide, and touch — first in simulation, then for real.*

<br>

[![Email](https://img.shields.io/badge/onlyho12@gmail.com-1a1a1a?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:onlyho12@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1a1a1a?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/hyeonho-shin-a219023a8)

<br>

</div>

---

<br>

## About

I build systems where a robot has to understand a physical surface and act on it.

Most of my work lives at the seam between **simulation and reality** — a digital twin in Isaac Sim that learns a polishing motion, a TurtleBot that patrols a map and decides what it's looking at. I like the problems where perception, control, and learning can't be solved separately.

Currently focused on:

- **Robotics & ROS2** — motion control, multi-robot coordination, Nav2 / SLAM
- **Deep Learning** — behavioral cloning, reinforcement learning for manipulation
- **Computer Vision** — detection, depth sensing, point clouds
- **Digital Twin** — NVIDIA Isaac Sim, contact physics, sim-to-real pipelines

<br>

## Writing in Code

<br>

### 🏭 [PolyTwin](https://github.com/onlyho12-sketch/PolyTwin)

**A digital twin that learns to polish a car body.**

Three Doosan M0609 arms — ceiling and side mounted — polish an autonomous car body inside NVIDIA Isaac Sim. The interesting part isn't the simulation; it's the pipeline through it: rule-based motion becomes a **behavioral cloning** dataset, a **PPO residual policy** refines it, and the result is validated against **20° gloss measurements** before anything reaches a monitoring console.

`Isaac Sim 6.0.1` · `PyTorch 2.7 + CUDA` · `PPO` · `RMPFlow` · `Node.js` · `SQLite`

<br>

### 🎯 [SOCAMACA](https://github.com/onlyho12-sketch/SOCAMACA)

**An autonomous combat robot with a human in the loop.**

A TurtleBot4 patrols a mapped space using SLAM and Nav2, detects targets with YOLO, and computes an aim solution — then *stops* and waits. Nothing fires without operator approval through the web UI. Building it meant coordinating a detection node, a state-machine mission manager, and two separate frontends across ROS2 and rosbridge.

`ROS2 Humble` · `YOLO` · `Nav2 / SLAM` · `FastAPI` · `React` · `OAK-D` · `Arduino`

<br>

### 🔧 [cacadaca](https://github.com/onlyho12-sketch/cacadaca)

**From a 3D scan to a sanded bonnet, end to end.**

A full four-stage pipeline: a virtual depth camera captures the car bonnet as a **point cloud**, a path generator raster-scans it with surface normal estimation, multiple robot arms execute the polish under **virtual-spring contact force control** (~1.5N), and a browser dashboard charts the forces live. The groundwork that PolyTwin grew out of.

`Isaac Sim` · `ROS2 Humble` · `Open3D / PLY` · `Vite` · `Chart.js` · `WebSocket`

<br>

## Toolbox

<div align="center">

![Python](https://img.shields.io/badge/Python-1a1a1a?style=flat-square&logo=python&logoColor=3776AB)
![C++](https://img.shields.io/badge/C++-1a1a1a?style=flat-square&logo=cplusplus&logoColor=00599C)
![PyTorch](https://img.shields.io/badge/PyTorch-1a1a1a?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![ROS2](https://img.shields.io/badge/ROS2-1a1a1a?style=flat-square&logo=ros&logoColor=22314E)
![NVIDIA](https://img.shields.io/badge/Isaac%20Sim-1a1a1a?style=flat-square&logo=nvidia&logoColor=76B900)
![OpenCV](https://img.shields.io/badge/OpenCV-1a1a1a?style=flat-square&logo=opencv&logoColor=5C3EE8)

![React](https://img.shields.io/badge/React-1a1a1a?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-1a1a1a?style=flat-square&logo=fastapi&logoColor=009688)
![Node.js](https://img.shields.io/badge/Node.js-1a1a1a?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![Linux](https://img.shields.io/badge/Ubuntu-1a1a1a?style=flat-square&logo=ubuntu&logoColor=E95420)
![Docker](https://img.shields.io/badge/Docker-1a1a1a?style=flat-square&logo=docker&logoColor=2496ED)
![Git](https://img.shields.io/badge/Git-1a1a1a?style=flat-square&logo=git&logoColor=F05032)

</div>

<br>

---

<div align="center">

<br>

*Thanks for stopping by.*

**[onlyho12@gmail.com](mailto:onlyho12@gmail.com)**  ·  **[LinkedIn](https://www.linkedin.com/in/hyeonho-shin-a219023a8)**

<br>

</div>
