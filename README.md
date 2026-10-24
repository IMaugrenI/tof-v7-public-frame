# Architecture Reference — System Boundaries (V7)

<p align="center">
  <img src="https://raw.githubusercontent.com/IMaugrenI/IMaugrenI/main/assets/banner/ToF_Banner.png" alt="ToF Systems architecture banner" width="100%" />
</p>

**How to separate responsibilities, data spaces, and operational authority in a local-first system.**

This repository documents a **reduced public architecture reference** from an earlier, version-tagged stage of ToF development. The repository name retains **V7** for continuity with existing links and documentation. You do **not** need to know the internal version history to use the ideas presented here.

[Deutsch](README_DE.md) · [Start here](START_HERE.md) · [Project overview](https://github.com/IMaugrenI/tof-showcase)

## The architectural question

How can a larger local system remain understandable and controlled when it has different sources of information, stages of processing, planning work, and operational services?

This reference examines the separation of:
- **Runtime:** what is actually executing.
- **Canon:** explicitly governed and accepted reference material.
- **Archive:** retained material that is not automatically active runtime authority.
- **Workbench (Werkbank):** preparation, investigation, and review outside runtime.
- **Bridge planning:** translation of prepared material into possible next steps, without silently making it executable.

These terms describe **responsibility boundaries**, not proof of a deployed implementation.

## Read the reference

| Document | Focus |
| --- | --- |
| [Core frame](docs/01_core_frame.md) | The reduced public architectural view. |
| [Space boundaries](docs/02_space_boundaries.md) | Why distinct areas and their responsibilities should stay separate. |
| [Public guardrails](docs/03_public_guardrails.md) | Limits on what may be inferred or exposed publicly. |
| [Processing chain](docs/04_public_chain.md) | How to interpret the reduced chain. |
| [Service map](docs/05_reduced_service_map.md) | A limited, redacted service relationship view. |
| [Reading rules](docs/06_reading_rules.md) | Distinguishing documentation, proposals, and operational evidence. |

## Why this remains public

The useful part is the **method**: make ownership explicit, protect boundaries, preserve provenance, and distinguish proposals from accepted and running states. Those principles can be considered independently of a particular internal version number.

The reference may help readers interested in local-first system architecture, service separation, reviewable technical documentation, and authority boundaries.

## What it does not claim

This repository does not contain a production runtime, a complete private service map, credentials, or a full implementation of everything described. Public diagrams and terminology are **architecture descriptions**, not evidence that a particular service is active or a product has reached production readiness.

For currently usable public tools, visit [ToF Showcase](https://github.com/IMaugrenI/tof-showcase) or the [GitHub profile](https://github.com/IMaugrenI). Each product repository documents its own capabilities and operating path.
