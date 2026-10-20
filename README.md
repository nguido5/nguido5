# Hi, I'm Nicholas Guido

**Aerospace Engineering @ Georgia Tech** · B.S., Minor in Computing & Intelligence · GPA 4.0 · Class of 2028

I'm interested in **guidance, navigation, and control (GNC)** and autonomy for aerospace and robotic systems. I like the full loop: estimating state from noisy sensors, planning under uncertainty, closing the control loop, and then building the test rigs and simulators that show whether it actually works.

**Portfolio: [nguido5.github.io](https://nguido5.github.io)** has architecture diagrams, results, and write-ups for everything below.

---

## What I work on

| Area | What I've built |
|---|---|
| **Estimation & navigation** | A 64-state HMM/POMDP belief tracker that fuses noisy acoustic and distance observations with Bayesian updates, with JIT-compiled JAX kernels for fast forward belief rollouts |
| **Guidance & planning** | A real-time iterative-deepening alpha-beta planner with a transposition table and expected-value sensing arbitration under a hard compute clock |
| **Control** | PID tuning and flight testing on a Betaflight FPV quadcopter; watchdog-protected motor control with closed-loop RPM acceptance tests |
| **Flight dynamics & simulation** | A C++ aircraft performance simulator (ISA atmosphere, drag polar, propeller/turbojet/turbofan models, climb, ceiling, and turn solvers), building toward 6-DOF trajectory simulation |
| **Test & validation** | A full-stack hardware-in-the-loop motor DVT rig and a ROS/MCAP telemetry validator checked against 20,000 lb test runs |
| **CFD** | Multi-element NACA 4412 RANS analysis in ANSYS Fluent (slat/flap trade study) |

## Code

- [POMDP planning agent & tournament benchmark harness](https://github.com/Yoloholoknow/3600-tournament)

## Explore the portfolio

- [Software & Autonomy](https://nguido5.github.io/software.html): POMDP planning agent, benchmark harness, engine RUL scheduler
- [Aerospace Analysis](https://nguido5.github.io/aerospace.html): flight dynamics simulator, airfoil CFD
- [Hardware & Design](https://nguido5.github.io/hardware.html): custom FPV quadcopter, lunar EVA boot sensor platform
- [Test & Validation](https://nguido5.github.io/validation.html): HIL motor rig, ROS/MCAP validator, destructive DVT

## Experience & recognition

- **Robotics Engineering Intern**, Slip Robotics (Summer 2026)
- **Undergraduate Researcher**, Georgia Tech, Dr. John Dec: flight performance simulation (current)
- **Researcher**, Aerospace Systems Design Laboratory: turbofan degradation modeling and RUL scheduling
- **1st Place**, GT AIAA AE Hackathon (Feb 2026): lunar EVA boot multi-sensor fusion concept

## Tools

- **Languages:** C++, Python, MATLAB/Simulink, Java, SQL
- **Frameworks & tools:** ROS, Foxglove, JAX/NumPy, FastAPI, Docker/WSL2, LabJack DAQ, ANSYS Fluent, Git/GitHub
- **Concepts:** Bayesian state estimation (HMM/POMDP, Kalman filters), PID control, alpha-beta search, 6-DOF dynamics

## Get in touch

[Email](mailto:nicholasguido16@gmail.com) · [LinkedIn](https://linkedin.com/in/nicholas-guido/) · [Portfolio](https://nguido5.github.io)
