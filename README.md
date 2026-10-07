## Prakhar Gupta

Student researcher at **IIIT Hyderabad**, working on **autonomous aerial robotics** and **digital hardware design**.

I work on making drones perceive, track, and coordinate on their own: multi-agent reinforcement learning for swarms at the Robotics Research Center, and vision-based target following on real quadrotors. Separately, I design hardware down to the transistor: RISC-V cores, FPGA accelerators, and custom SRAM.

- 🏆 **Finalist** in the MathWorks Minidrone Competition (India, 2025)
- 🔬 Currently: decentralized swarm coordination with MADDPG → recurrent MAPPO at RRC, IIIT Hyderabad

---

### 🚁 Robotics & Autonomy

| Project | What it is | Stack |
| --- | --- | --- |
| [**Swarm Drone Coordination**](https://github.com/pg1590/Swarm-Drones-Detection-Tracking-Path-Prediction-and-Navigation) | Decentralized multi-UAV target pursuit, formation control, and collision avoidance trained with MARL (CTDE) | Python · PyBullet · MADDPG / MAPPO |
| [**Vision-Based Target-Following Drone**](https://github.com/pg1590/vision-based-target-following-drone-sim) | A Tello chaser drone that detects another drone with YOLOv8 and pursues it with PID control across figure-8, helix, spiral, and zig-zag paths | Python · YOLOv8 · OpenCV · djitellopy |
| [**MathWorks Minidrone Line Follower**](https://github.com/pg1590/mathworks-minidrone-line-follower) | Competition finalist: red-line tracking, arc look-ahead, and landing-marker detection for a Parrot minidrone | MATLAB · Simulink · Stateflow |

### 🔧 Hardware & Architecture

| Project | What it is | Stack |
| --- | --- | --- |
| [**HLS GEMM Accelerators**](https://github.com/pg1590/HLS-GEMM-Accelerators-on-AMD-Xilinx-FPGA) | Design-space exploration of matrix-multiply kernels on an Alveo U50: tiling, systolic PE arrays, dataflow, double buffering, INT8 | C++ · Vitis HLS · XRT |
| [**RISC-V Core**](https://github.com/pg1590/RISC-V-Core) | Sequential and pipelined RV processors with forwarding and hazard detection | Verilog · GTKWave |
| [**32×32 SRAM with Decoder**](https://github.com/pg1590/32x32-SRAM-Module-with-a-Decoder) | Transistor-level 6T SRAM macro with a 5:32 decoder and sense amplifier, 78.3 ps end-to-end at 0.9 V | Cadence Virtuoso |
| [**4-Stage Audio Amplifier**](https://github.com/pg1590/4-stage-Audio-Amp-) | Pre-amp → gain → band-pass → Class-AB power stage, simulated and built in hardware | LTspice |

### 💻 Systems & Software

| Project | What it is | Stack |
| --- | --- | --- |
| [**xv6 Extensions**](https://github.com/pg1590/Xv6) | New syscalls (syscall counting, alarms) plus lottery and MLFQ schedulers in the xv6 kernel | C · RISC-V |
| [**Unix Shell**](https://github.com/pg1590/C-shell) | A POSIX-style shell with pipes, redirection, job control, and signal handling | C · Linux |
| [**AI Site Builder**](https://github.com/pg1590/AI-Website-Builder) | Full-stack SaaS that generates and iterates websites from prompts, with auth, versioning, and Stripe billing | React · TypeScript · Express · Prisma |
| [**Cancer Stratification System**](https://github.com/pg1590/Cancer-Stratification-System) | Chest X-ray risk assessment with an XGBoost pipeline behind a role-based web app | Python · XGBoost · Node.js · React |

---

### Tools I work with

**Robotics:** PyBullet · MATLAB/Simulink · OpenCV · YOLOv8<br>
**Hardware:** Verilog · Vitis HLS · Cadence Virtuoso · Xilinx FPGAs<br>
**Languages:** C · C++ · Python · TypeScript
