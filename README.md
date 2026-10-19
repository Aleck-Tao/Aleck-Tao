# Yuanyuan Tao (Alec)

MSc Electronic Engineering candidate, Durham University.

My interests are in sensing and control, including autonomous systems and wearable measurements. I focus on what changes when the inputs are imperfect: timestamps drift, measurements become unreliable, or a learned controller encounters model uncertainty.

The [research portfolio](https://github.com/Aleck-Tao/computer-vision-autonomous-systems-portfolio) brings together UAV field footage, software experiments and analysis. The individual projects are below.

## Wearable signal evaluation

[REHAB wearable signal audit](https://github.com/Aleck-Tao/rehab-wearable-signal-audit) examines 4,257 paired records from a public rehabilitation dataset. It compares window, record and exact-content holdouts, then isolates limb and glove signal contributions with a fixed baseline. Published integrity checks and aggregate results are reproducible; a local replay also produces split assignments and held-out predictions.

## Sensing and mission handling

| Project | What to look at |
|---|---|
| [UAV multisensor diagnostics](https://github.com/Aleck-Tao/uav-multisensor-diagnostics) | 35 matched-noise runs isolate timing and trajectory faults, including a local position error missed by the current aggregate gates. |
| [Flight-video quality audit](https://github.com/Aleck-Tao/uav-flight-video-quality-audit) | Two released outdoor clips, a 224-frame audit and a 10 Hz follow-up examining a flagged interval and its scene transition. |
| [Mission interface](https://github.com/Aleck-Tao/safety-constrained-uav-mission-interface) | Constrained-language parsing, strict JSON types and regression-tested rejection of ambiguous safety instructions. |
| [Thermal validation toolkit](https://github.com/Aleck-Tao/multichannel-thermal-validation-toolkit) | Paired common-mode/reference controls demonstrate which calibration errors cross-channel agreement cannot detect. |

## Control and networked systems

| Project | What to look at |
|---|---|
| [Runtime evidence assurance](https://github.com/Aleck-Tao/runtime-safety-assurance-uav) | 360 synthetic telemetry replays measure short-event recall, trigger delay, noisy action episodes and recovery under different thresholds and persistence. |
| [Safe neural control certificates](https://github.com/Aleck-Tao/safe-neural-control-certificates) | Scalar robust projection with classical baselines; a 126-rollout contraction sweep connects analytic feasibility margins to intervention and cost. |
| [Decentralized learning stress test](https://github.com/Aleck-Tao/decentralized-learning-stress-test) | An eight-peer Adult benchmark with sender-level trimming diagnostics, including tied coordinates and clean/poisoned comparisons. |
| [Wireless deadline lab](https://github.com/Aleck-Tao/wireless-tsn-deadline-lab) | C++ packet/slot simulation with 160 paired-seed runs comparing clock estimators and uncertainty margins alongside the original four-scheduler benchmark. |

Each project links its results to the data, configuration and commands used to produce them. My current research question is how timing and model uncertainty should change a system's decision to proceed, constrain an action or request better evidence.

[yuanyuan.tao@durham.ac.uk](mailto:yuanyuan.tao@durham.ac.uk)
