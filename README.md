# Yuanyuan Tao (Alec)

MSc Electronic Engineering candidate, Durham University.

My interests are in sensing and control for autonomous systems. I focus on what changes when the inputs are imperfect: timestamps drift, measurements become unreliable, or a learned controller encounters model uncertainty.

The [research portfolio](https://github.com/Aleck-Tao/computer-vision-autonomous-systems-portfolio) brings together UAV field footage, software experiments and analysis. The individual projects are below.

## Sensing and mission handling

| Project | What to look at |
|---|---|
| [UAV multisensor diagnostics](https://github.com/Aleck-Tao/uav-multisensor-diagnostics) | A fault-injection case with nearly normal average sensor rates but 18.314 ms p95 camera–LiDAR timing mismatch. The analysis checks timing, sequence loss and trajectory error separately. |
| [Flight-video quality audit](https://github.com/Aleck-Tao/uav-flight-video-quality-audit) | Analysis of two released outdoor clips: 224 sampled frames, with two low-sharpness samples in Clip B. Includes the videos, frame metrics and timeline. |
| [Mission interface](https://github.com/Aleck-Tao/safety-constrained-uav-mission-interface) | A rule-based parser and structured checks for speed, clearance and fallback behavior. The contract makes the decision available for inspection before execution. |
| [Thermal validation toolkit](https://github.com/Aleck-Tao/multichannel-thermal-validation-toolkit) | Synthetic multichannel data with offset, drift and status faults; separate channel and reference metrics help explain each failure. |

## Control and networked systems

| Project | What to look at |
|---|---|
| [Runtime evidence assurance](https://github.com/Aleck-Tao/runtime-safety-assurance-uav) | Synthetic telemetry replay connecting monitor persistence, stopping margins and fallback recommendations. |
| [Safe neural control certificates](https://github.com/Aleck-Tao/safe-neural-control-certificates) | A learned policy with an analytic robust projection for a scalar sampled-data model; classical baselines and counterexamples show where each guarantee comes from. |
| [Decentralized learning stress test](https://github.com/Aleck-Tao/decentralized-learning-stress-test) | An eight-peer Adult benchmark examining the tradeoff between clean-data accuracy and resistance to poisoned updates. |
| [Wireless deadline lab](https://github.com/Aleck-Tao/wireless-tsn-deadline-lab) | A C++ packet/slot simulator comparing four schedulers. Clock-aware EDF helps in bursty-channel cases but loses to FIFO in the configured clock-holdover case. |

Each project links its results to the data, configuration and commands used to produce them. My current research question is how timing and model uncertainty should change a system's decision to proceed, constrain an action or request better evidence.

[yuanyuan.tao@durham.ac.uk](mailto:yuanyuan.tao@durham.ac.uk)
