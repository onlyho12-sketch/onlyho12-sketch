<div align="center">

<br>

# Hyeonho Shin

### Robotics · AI · Digital Twin

*Teaching robots to see, decide, and touch —*
*first in simulation, then for real.*

<br>

[![Email](https://img.shields.io/badge/Email-1a1a1a?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:onlyho12@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1a1a1a?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/hyeonho-shin-a219023a8)

<br>

</div>

<br>

## &nbsp;About

I build systems where a robot has to understand a physical surface and act on it.

Most of my work lives at the seam between **simulation and reality** — a digital twin that learns a polishing motion, a mobile robot that patrols a map and decides what it's looking at. I'm drawn to the problems where perception, control, and learning can't be solved separately.

|  | Focus |
|:--|:--|
| **Robotics** | ROS2 · motion control · multi-robot coordination · Nav2 / SLAM |
| **Deep Learning** | behavioral cloning · reinforcement learning for manipulation |
| **Vision** | object detection · depth sensing · point clouds |
| **Digital Twin** | Isaac Sim · contact physics · sim-to-real pipelines |

<br>

## &nbsp;Selected Work

<br>

### 🏭 &nbsp;[PolyTwin](https://github.com/onlyho12-sketch/PolyTwin)

> **A digital twin that learns to polish a car body.**

Three Doosan M0609 arms polish a car body inside NVIDIA Isaac Sim.
The interesting part isn't the simulation — it's the pipeline through it.

Rule-based motion becomes a **behavioral cloning** dataset, a **PPO residual
policy** refines it, and the result is validated against **20° gloss
measurements** before anything reaches the monitoring console.

<kbd>Isaac Sim</kbd> <kbd>PyTorch + CUDA</kbd> <kbd>PPO</kbd> <kbd>RMPFlow</kbd> <kbd>Node.js</kbd>

<br>

### 🎯 &nbsp;[SOCAMACA](https://github.com/onlyho12-sketch/SOCAMACA)

> **An autonomous combat robot that waits for permission.**

A TurtleBot4 patrols a mapped space with SLAM and Nav2, detects targets
with YOLO, computes an aim solution — then *stops*.

Nothing fires without operator approval through the web UI. Building it meant
coordinating a detection node, a state-machine mission manager, and two
separate frontends across ROS2 and rosbridge.

<kbd>ROS2 Humble</kbd> <kbd>YOLO</kbd> <kbd>Nav2 / SLAM</kbd> <kbd>FastAPI</kbd> <kbd>React</kbd> <kbd>OAK-D</kbd>

<br>

### 🧠 &nbsp;[Dittobot](https://github.com/onlyho12-sketch/Dittobot)

> **Teaching a robot a skill by showing it once.**

An RGB-D demonstration is decomposed into trajectory analysis and bounded
semantic analysis, then compiled deterministically into a validated `SkillGraph`.

Built around an honest **safety gate design** — hardware execution stays closed
behind explicit authorization flags, and the full Teaching → Registry → Runtime
loop runs offline against a mock adapter when no robot is present.

<kbd>Python 3.10</kbd> <kbd>FastAPI</kbd> <kbd>RealSense D435i</kbd> <kbd>ROS2</kbd> <kbd>MoveIt</kbd>

<br>

### 🍳 &nbsp;[BOKABOKA](https://github.com/onlyho12-sketch/BOKABOKA)

> **A collaborative robot that cooks, and takes your order by QR.**

A Doosan M0609 with an RG2 gripper cooks *jeon* and fried rice on a wok.
Customers order from their phone; an admin dashboard starts the run.

The layer I care about most is **exception handling** — a safety monitor
watching for grip failure and force overruns, a recovery manager choosing
between auto-recovery and a human, and a physical E-STOP wired to digital I/O.

<kbd>ROS2 Humble</kbd> <kbd>Doosan M0609</kbd> <kbd>OnRobot RG2</kbd> <kbd>Modbus</kbd> <kbd>Flask</kbd>

<br>

### ♻️ &nbsp;[HI-CYCLE](https://github.com/onlyho12-sketch/HI-CYCLE)

> **Scoring a hydraulic cylinder's health, then paying you for it.**

*2026 HD Future Construction Machinery Challenge — Track 2, Sustainability.*

Five sensor streams collapse into one weighted **Health Index**, graded A–D,
feeding an exponential degradation model for **RUL prediction** with confidence
intervals. That grade then drives a buyback credit — closing the loop into a
circular economy at roughly **55% cost saving** per remanufactured cylinder.

<kbd>React 18</kbd> <kbd>Vite</kbd> <kbd>Recharts</kbd> <kbd>Unity WebGL</kbd> <kbd>Simulink</kbd>

<br>

### 🔧 &nbsp;[cacadaca](https://github.com/onlyho12-sketch/cacadaca)

> **From a 3D scan to a sanded bonnet, end to end.**

A virtual depth camera captures the bonnet as a **point cloud**, a generator
raster-scans it with surface normal estimation, and multiple arms execute the
polish under **virtual-spring contact force control** at ~1.5N.

The groundwork PolyTwin grew out of.

<kbd>Isaac Sim</kbd> <kbd>ROS2 Humble</kbd> <kbd>Open3D</kbd> <kbd>Vite</kbd> <kbd>Chart.js</kbd>

<br>

## &nbsp;Toolbox

<div align="center">

<br>

![Python](https://img.shields.io/badge/Python-1a1a1a?style=flat-square&logo=python&logoColor=3776AB)
![C++](https://img.shields.io/badge/C++-1a1a1a?style=flat-square&logo=cplusplus&logoColor=00599C)
![PyTorch](https://img.shields.io/badge/PyTorch-1a1a1a?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![ROS2](https://img.shields.io/badge/ROS2-1a1a1a?style=flat-square&logo=ros&logoColor=22314E)
![Isaac Sim](https://img.shields.io/badge/Isaac%20Sim-1a1a1a?style=flat-square&logo=nvidia&logoColor=76B900)
![OpenCV](https://img.shields.io/badge/OpenCV-1a1a1a?style=flat-square&logo=opencv&logoColor=5C3EE8)

![React](https://img.shields.io/badge/React-1a1a1a?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-1a1a1a?style=flat-square&logo=fastapi&logoColor=009688)
![Flask](https://img.shields.io/badge/Flask-1a1a1a?style=flat-square&logo=flask&logoColor=ffffff)
![Node.js](https://img.shields.io/badge/Node.js-1a1a1a?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![Ubuntu](https://img.shields.io/badge/Ubuntu-1a1a1a?style=flat-square&logo=ubuntu&logoColor=E95420)
![Docker](https://img.shields.io/badge/Docker-1a1a1a?style=flat-square&logo=docker&logoColor=2496ED)

<br>

</div>

<br>

---

<div align="center">

<br>

*Thanks for stopping by.*

<br>

[![Email](https://img.shields.io/badge/onlyho12@gmail.com-1a1a1a?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:onlyho12@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1a1a1a?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/hyeonho-shin-a219023a8)

<br>

</div>
