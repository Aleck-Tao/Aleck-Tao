# Yuanyuan Tao (Alec)

MSc Electronic Engineering candidate at Durham University, preparing for PhD research in trustworthy autonomous systems, computer vision, multimodal perception, and experimental sensing.

I work across the boundary between algorithms and physical evidence: defining typed interfaces around learned components, checking whether sensor streams are trustworthy before using them, and packaging experiments so another researcher can reproduce the decision from committed data and code.

> **Research approach:** field evidence → integrity checks → interpretable metrics → explicit safety/quality gates → reproducible reports

## Research portfolio

| Repository | Research focus | Public evidence |
|---|---|---|
| [UAV multisensor diagnostics](https://github.com/Aleck-Tao/uav-multisensor-diagnostics) | Sensor timing, Camera–LiDAR synchronization, trajectory evaluation, failure injection | Importable Python package, CLI, five tests, ATE/RPE and timing reports, CI-reproduced baseline/degraded benchmark |
| [Safety-constrained UAV mission interface](https://github.com/Aleck-Tao/safety-constrained-uav-mission-interface) | Safe boundary between language-level intent and UAV execution | Typed mission contract, JSON Schema, fail-closed policy, threat model, seven tests, deterministic batch evidence |
| [Runtime evidence assurance for UAV telemetry](https://github.com/Aleck-Tao/runtime-safety-assurance-uav) | Bounded STPA-informed hazard-to-evidence traceability and persistence-qualified fallback recommendations | Released v0.1.0 synthetic open-loop replay, executable claim/monitor mapping, hash-bound source/data/results, six-job CI |
| [Safe neural control certificates](https://github.com/Aleck-Tao/safe-neural-control-certificates) | Analytic robust projection around a learned policy for an uncertain sampled-data plant | Released v0.1.0, separate-code-path certificate recomputation, explicit counterexamples, 90 simulated scalar-model closed-loop runs, 36,012 corner/grid checks, six-job CI |
| [Decentralized learning stress test](https://github.com/Aleck-Tao/decentralized-learning-stress-test) | Peer-to-peer learning under non-IID scarcity, malicious updates, synthetic-data poisoning, and membership auditing | Released v0.1.0, pinned UCI Adult source, 54-run CPU benchmark, 19 tests, three verified result chains, Windows/Linux CI |
| [Wireless TSN deadline lab](https://github.com/Aleck-Tao/wireless-tsn-deadline-lab) | Deadline scheduling across a Qbv-inspired wired boundary and lossy wireless slot abstraction | Released v0.1.0, C++20, GCC/Clang and sanitizer CI, 18 Python evaluator tests, 240 CI runs, 725 hash-verified result files |
| [UAV flight-video quality audit](https://github.com/Aleck-Tao/uav-flight-video-quality-audit) | Computer-vision evidence quality and data provenance | Two released field-test videos, SHA-256 manifest, 224 sampled frames, per-frame metrics, SVG timeline, CI reproduction |
| [Multichannel thermal validation toolkit](https://github.com/Aleck-Tao/multichannel-thermal-validation-toolkit) | Embedded sensing, defensive protocol parsing, experimental validation | Fictional public protocol, seeded simulator, status-aware analysis, nine tests, synthetic baseline/fault-injected reports |
| [Computer vision and autonomous systems portfolio](https://github.com/Aleck-Tao/computer-vision-autonomous-systems-portfolio) | Integrated research narrative and physical UAV evidence | Stable CV-facing entry point, project map, field media, evidence boundaries, reproducibility instructions |

## Current research directions

- **Trustworthy multimodal perception:** synchronization, provenance, uncertainty-aware diagnostics, and failure analysis for camera/LiDAR systems.
- **Safety-constrained embodied AI:** structured mission representations and deterministic runtime guards around language- or vision-conditioned components.
- **Safe learning-based control:** composing learned nominal policies with explicit model-based constraints and falsifiable closed-loop certificates.
- **Trustworthy decentralized AI:** peer-local learning, non-IID data, malicious-update stress tests, privacy auditing, and explicit protocol boundaries.
- **Time-sensitive networked systems:** deadline scheduling, clock uncertainty, loss bursts, reliability mechanisms, and provenance-checked simulation.
- **Experimental robotics:** connecting physical tests with traceable metrics instead of treating a demonstration video as sufficient evidence.
- **Embedded and industrial sensing:** reliable data acquisition, status-aware decoding, multichannel consistency, and reproducible validation workflows.

## Evidence principles

Every featured repository separates what is measured from what is simulated. Controlled benchmarks are labelled as synthetic; field videos are presented as physical-test evidence but not as proof of autonomy; commercial identifiers, proprietary protocols, and client data are not published. Each software repository includes tests, versioned configuration, machine-readable outputs, and GitHub Actions.

## Selected reproducible results

| Result | Interpretation |
|---|---|
| Multisensor baseline: ATE RMSE 0.0370 m; sync p95 2.206 ms; 0 failed gates | Controlled synthetic baseline for the public diagnostic pipeline—not a field-accuracy claim |
| Multisensor degraded case: ATE RMSE 0.2119 m; sync p95 18.314 ms; 11 failed gates | Fault injection is detected and reported with coded failures |
| Video audit: 224 decoded field-video samples | Demonstrates provenance and image-quality analysis over released real media |
| Thermal baseline: p95 channel spread 0.3026 °C; 0 issues | Seeded synthetic regression fixture—not a product specification |
| Thermal degraded case: p95 channel spread 1.1843 °C; 8 issues | Status faults, channel offset, drift, and spread gates behave as designed |
| Decentralized sign-flip case: peer mean 0.484 vs 0.729 clean synthetic mix; trimmed mean 0.677 under attack | One Adult/all-to-all/three-seed stress test; evidence of a configured failure mode, not a general Byzantine guarantee |
| Wireless release matrix: 240 CI runs; clock-aware EDF improves on FIFO in bursty/retry cases but loses under sync holdover | Retained mixed result from a packet/slot simulator, not a standards, hardware, or universal scheduler claim |

## Contact

- Email: [yuanyuan.tao@durham.ac.uk](mailto:yuanyuan.tao@durham.ac.uk)
- GitHub: [@Aleck-Tao](https://github.com/Aleck-Tao)
