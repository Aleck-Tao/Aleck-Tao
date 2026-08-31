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
| [Safe neural control certificates](https://github.com/Aleck-Tao/safe-neural-control-certificates) | Analytic robust projection around a learned policy for an uncertain sampled-data plant | Released v0.1.0, independently recomputed certificate margins, explicit counterexamples, 90 closed-loop runs, 36,012 corner/grid checks, six-job CI |
| [UAV flight-video quality audit](https://github.com/Aleck-Tao/uav-flight-video-quality-audit) | Computer-vision evidence quality and data provenance | Two released field-test videos, SHA-256 manifest, 224 sampled frames, per-frame metrics, SVG timeline, CI reproduction |
| [Multichannel thermal validation toolkit](https://github.com/Aleck-Tao/multichannel-thermal-validation-toolkit) | Embedded sensing, defensive protocol parsing, experimental validation | Fictional public protocol, seeded simulator, status-aware analysis, nine tests, synthetic baseline/fault-injected reports |
| [Computer vision and autonomous systems portfolio](https://github.com/Aleck-Tao/computer-vision-autonomous-systems-portfolio) | Integrated research narrative and physical UAV evidence | Stable CV-facing entry point, project map, field media, evidence boundaries, reproducibility instructions |

## Current research directions

- **Trustworthy multimodal perception:** synchronization, provenance, uncertainty-aware diagnostics, and failure analysis for camera/LiDAR systems.
- **Safety-constrained embodied AI:** structured mission representations and deterministic runtime guards around language- or vision-conditioned components.
- **Safe learning-based control:** composing learned nominal policies with explicit model-based constraints and falsifiable closed-loop certificates.
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

## Contact

- Email: [yuanyuan.tao@durham.ac.uk](mailto:yuanyuan.tao@durham.ac.uk)
- GitHub: [@Aleck-Tao](https://github.com/Aleck-Tao)
