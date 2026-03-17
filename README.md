Line-Following Robot with PID Control 
Overview
This project implements a Differential-Drive Robot that tracks a predefined path using a PID Controller. The system is built on a Three-Client Architecture communicating over the Innexis Virtual System Interconnect (IVSI) backplane.

Architecture
The system consists of three independent Python clients:

Client 1 (Simulator): Handles robot kinematics, environment physics, and adds sensor noise/disturbances.

Client 2 (Controller): Implements a PID control law to minimize lateral and heading errors.

Client 3 (Visualizer/Logger): Real-time plotting of trajectory vs. path and logging of KPIs.

Experiments & Results
This repository contains multiple experiments as required by the course:

Experiment 1: PID Gain Sweep (Main Branch)
Analyzed robot performance across 3 sets of PID gains.

Key Metrics: Overshoot, Settling Time, and Steady-State Error.

Refer to the report for detailed KPI tables.

Other Experiments > Note: Please switch to the other branch to view the source code for:

E2 - Curved Path Robustness: Tracking piecewise circular arcs and Bezier-like paths.
E3 - Noise Rejection: Testing robustness under varying Gaussian noise levels.
E4 - PD vs. PID Ablation: Comparative study between PD and PID controllers under noisy conditions.

## Deliverables
- Report: [https://drive.google.com/file/d/1pqX64lm1gtA6popkjMF3nCYRh9q9zC3t/view?usp=sharing]
- Screencast: [Google Drive Link](https://drive.google.com/file/d/1Zyv6bihSF6t6rktzEoQRSClAKF6Hi9n6/view?usp=drivesdk)]
