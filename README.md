<div align="center">

<h1>Muksitul Ziad</h1>

<p>
  <strong>Robotics Software &amp; Systems · Autonomous Ground &amp; Aerial Robots</strong><br>
  Software Team Lead, Mars Rover Team · <strong>AIUB Robotics Crew</strong><br>
  American International University-Bangladesh (AIUB)
</p>


<p>
  
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Gazebo-E66B0B?style=flat-square" alt="Gazebo" />
  <img src="https://img.shields.io/badge/ArduPilot-264C3B?style=flat-square" alt="ArduPilot" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
</p>

</div>

---

## About

I work across robotics software and system integration for ground rovers and aerial robots. My core interest lies in how **autonomy, perception, control, and communication** fit together as a coupled system—and what happens when the modeling or environmental assumptions behind them stop holding.

As **Software Team Lead for the Mars Rover Team at AIUB Robotics Crew**, I lead software architecture and integration for rover locomotion control, wireless telemetry, and remote operation, focusing on the interaction between onboard compute, communication links, and the ground control station.

Beyond planetary rovers, my project experience spans autonomous drones, multi-agent swarm coordination, inter-drone communication, and autonomous drone interception systems. I use **ROS 2, Gazebo, and ArduPilot** to develop and evaluate robotic systems, with research interests centered on reliable field autonomy and coordinated multi-robot behavior under practical sensing, compute, and connectivity constraints.

---

## Systems and Project Directions

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Ground &amp; Planetary Robotics</strong>
      <ul>
        <li><strong>Rover Software Integration:</strong> Modular ROS 2 pipelines connecting onboard control, state estimation, and system diagnostics.</li>
        <li><strong>Telemetry &amp; Remote Operation:</strong> Wireless communication architectures and operator interfaces engineered for responsiveness under degraded links.</li>
        <li><strong>Simulation-to-Field Validation:</strong> Testing locomotion and autonomy in Gazebo while carefully separating simulation behavior from hardware constraints.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <strong>Aerial Autonomy &amp; Multi-Robot Systems</strong>
      <ul>
        <li><strong>Autonomous UAV Pipelines:</strong> Onboard guidance, navigation, and control built on ArduPilot and ROS 2.</li>
        <li><strong>Swarm &amp; Inter-Drone Coordination:</strong> Linking local autonomy with inter-agent communication for coordinated multi-robot behavior.</li>
        <li><strong>Autonomous Drone Interception:</strong> Real-time target tracking, state estimation, and trajectory planning under tight latency budgets.</li>
      </ul>
    </td>
  </tr>
</table>

<br>

| Active Direction | Engineering & Research Questions |
| :--- | :--- |
| **Rover Software & Remote Operation** | Integrating onboard control, telemetry, and ground-station interfaces; evaluating system responsiveness and graceful recovery when wireless links degrade. |
| **Drone Autonomy & Coordination** | Connecting onboard UAV autonomy with resilient inter-drone communication and coordinated multi-agent execution. |
| **Simulation & Rigorous Evaluation** | Building repeatable test scenarios, documenting underlying assumptions, and clearly distinguishing simulation findings from physical hardware validation. |
| **Public Robotics Codebase** | Structuring reusable implementations, simulation templates, and technical notes for ground rovers and aerial platforms. |

<!-- Replace project entries with direct repository, demo, or technical report links as artifacts are published. -->

---

## Research Interests

- **Reliable Field Autonomy:** Navigation, localization, and fault recovery under imperfect sensing, dynamic terrain, and intermittent communication.
- **Multi-Robot Systems:** Decentralized coordination, information sharing, and how network latency or packet loss shapes collective behavior.
- **Embedded Perception:** Real-time detection, tracking, and the accuracy–latency trade-offs of onboard inference on edge hardware.
- **System Evaluation & Reproducibility:** Repeatable experiments, meaningful baselines, failure-mode analysis, and strict separation of measured results from assumptions.

<details>
<summary><strong>Technical topics under active study and development</strong></summary>

*These represent ongoing study, coursework, and investigation areas rather than a claim of uniform proficiency across every method.*

| Domain | Topics & Methods |
| :--- | :--- |
| **Navigation & Planning** | LiDAR and visual SLAM, occupancy grids, AMCL, graph- and sampling-based planners (`A*`, `D* Lite`, `Hybrid A*`, `RRT*`), local planners (`DWA`, `MPPI`), terrain-aware navigation, multi-robot exploration |
| **Control & State Estimation** | PID, state-space modeling, LQR, MPC, trajectory tracking, Kalman filtering (`KF`, `EKF`, `UKF`), error-state estimation (`ES-EKF`), multi-sensor fusion, factor-graph methods |
| **Perception & Edge Deployment** | Camera calibration, stereo depth, visual odometry, object detection, semantic segmentation, multi-object tracking, and embedded inference (`ONNX`, `TensorRT`, `PyTorch`) |
| **Robotics Mathematics** | Rigid-body transformations, `SO(3) / SE(3)`, forward and inverse kinematics, Jacobians, and numerical optimization |
| **Research Practice** | Literature review, baseline reproduction, ablation studies, repeated trials, statistical evaluation, `LaTeX`, and reference management |

</details>

---

## Engineering Toolkit

| Domain | Tools & Platforms |
| :--- | :--- |
| **Primary Languages** | ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Robotics & Simulation** | ![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white) ![Gazebo](https://img.shields.io/badge/Gazebo-E66B0B?style=flat-square) ![ArduPilot](https://img.shields.io/badge/ArduPilot-264C3B?style=flat-square) ![Nav2](https://img.shields.io/badge/Nav2-0B7285?style=flat-square) ![TF2](https://img.shields.io/badge/TF2-4353A3?style=flat-square) ![RViz2](https://img.shields.io/badge/RViz2-304E80?style=flat-square) |
| **Embedded & Edge Compute** | ![Jetson Orin Nano](https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white) |
| **Development & Integration** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Interfaces & Electronics** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![Multisim](https://img.shields.io/badge/Multisim-006845?style=flat-square) ![Proteus](https://img.shields.io/badge/Proteus-184A83?style=flat-square) ![EasyEDA](https://img.shields.io/badge/EasyEDA-1765F6?style=flat-square&logo=easyeda&logoColor=white) ![Cadence Virtuoso](https://img.shields.io/badge/Cadence_Virtuoso-B31B1B?style=flat-square) |

> **Current Engineering Priority:** Strengthening **modern C++ and Python** for real-time robotics—with deliberate focus on deterministic debugging, automated testing, memory safety, and maintainable system architecture.

---




