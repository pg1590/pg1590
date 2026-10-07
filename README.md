## Prakhar Gupta

Software and robotics developer at **IIIT Hyderabad**. I build autonomous drones and the software around them, from perception and multi-agent learning to full-stack applications.

On the robotics side, I work on drones that perceive, track, and coordinate on their own: multi-agent reinforcement learning for swarms at the Robotics Research Center, and vision-based target following on real quadrotors. On the software side, I build end-to-end products (LLM-powered web apps, ML pipelines with production backends) and systems code down to the OS kernel.

- 🏆 **Finalist** in the MathWorks Minidrone Competition (India, 2025)
- 🔬 Currently: decentralized swarm coordination with MADDPG → recurrent MAPPO at RRC, IIIT Hyderabad

---

### 🚁 Robotics & Autonomy

| Project | What it is | Stack |
| --- | --- | --- |
| [**Swarm Drone Coordination**](https://github.com/pg1590/Swarm-Drones-Detection-Tracking-Path-Prediction-and-Navigation) | Decentralized multi-UAV target pursuit, formation control, and collision avoidance trained with MARL (CTDE) | Python · PyBullet · MADDPG / MAPPO |
| [**Vision-Based Target-Following Drone**](https://github.com/pg1590/vision-based-target-following-drone-sim) | A Tello chaser drone that detects another drone with YOLOv8 and pursues it with PID control across figure-8, helix, spiral, and zig-zag paths | Python · YOLOv8 · OpenCV · djitellopy |
| [**Marker-Tracking Chaser Drone**](https://github.com/pg1590/UAV-Project) | Real-flight Tello pursuit of an ArUco-marked target with Kalman-filtered tracking, PID control, and logged tracking-error analysis | Python · OpenCV · Kalman filter |
| [**MathWorks Minidrone Line Follower**](https://github.com/pg1590/mathworks-minidrone-line-follower) | Competition finalist: red-line tracking, arc look-ahead, and landing-marker detection for a Parrot minidrone | MATLAB · Simulink · Stateflow |

### 💻 Software & AI

| Project | What it is | Stack |
| --- | --- | --- |
| [**AI Site Builder**](https://github.com/pg1590/AI-Website-Builder) | Full-stack SaaS that generates and iterates websites from prompts, with auth, version history, a public gallery, and Stripe credits | React · TypeScript · Express · Prisma · PostgreSQL |
| [**Cancer Stratification System**](https://github.com/pg1590/Cancer-Stratification-System) | X-ray risk assessment with an XGBoost pipeline behind a role-based web app for patients, doctors, and radiologists | Python · XGBoost · Node.js · React · MongoDB · Docker |
| [**AI Claims Assessment**](https://github.com/pg1590/AI-CLAIMS-ASSESMENT-FOR-CAR-INSURANCE) | Car-insurance claim triage: YOLOv8 damage detection, severity and cost estimation, and fraud checks | Python · YOLOv8 · Streamlit |
| [**xv6 Extensions**](https://github.com/pg1590/Xv6) | New syscalls (syscall counting, alarms) plus lottery and MLFQ schedulers in the xv6 kernel | C · RISC-V |
| [**Unix Shell**](https://github.com/pg1590/C-shell) | A POSIX-style shell with pipes, redirection, job control, and signal handling | C · Linux |

### 🔧 Hardware

| Project | What it is | Stack |
| --- | --- | --- |
| [**HLS GEMM Accelerators**](https://github.com/pg1590/HLS-GEMM-Accelerators-on-AMD-Xilinx-FPGA) | Matrix-multiply kernels on an Alveo U50 FPGA: tiling, systolic arrays, dataflow, INT8 | C++ · Vitis HLS |
| [**RISC-V Core**](https://github.com/pg1590/RISC-V-Core) | Sequential and pipelined processors with forwarding and hazard detection | Verilog |
| [**32×32 SRAM with Decoder**](https://github.com/pg1590/32x32-SRAM-Module-with-a-Decoder) | Transistor-level 6T SRAM macro, 78.3 ps end-to-end at 0.9 V | Cadence Virtuoso |

---

### Tools I work with

**Languages:** Python · C · C++ · TypeScript · JavaScript<br>
**Robotics & ML:** PyBullet · Stable-Baselines3 · Gymnasium · PyTorch · YOLOv8 · OpenCV · MATLAB/Simulink<br>
**Web & Backend:** React · Node.js · Express · Prisma · PostgreSQL · MongoDB · Docker<br>
**Hardware:** Verilog · Vitis HLS · Cadence Virtuoso
