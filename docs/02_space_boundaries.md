# Responsibility and Data-Space Boundaries

The earlier architecture reference labeled **V7** highlights a strict separation of data spaces and authority. These distinctions remain useful without knowing the version history.

## Spaces in the public model

| Space | Purpose | Not equivalent to |
| --- | --- | --- |
| **Runtime** | Actual active services and current operational state | Planning documents or archived evidence |
| **Canon (Kanon)** | Governed reference material | Current runtime state |
| **Archive (Archiv)** | Retained records and provenance | Automatically valid current facts |
| **Workbench (Werkbank)** | Inspection and preparation of older material | Approved and deployed changes |
| **Bridge planning (Vorplanung)** | Planning and reviewing possible next steps | Running implementation |

## Why this matters

Material can inform another area only through an **explicit, controlled transition** appropriate to the system. Historical evidence does not become current truth by default; a plan does not become executable code automatically; identity or presentation cannot replace technical controls.

This document shows conceptual boundary rules, **not** full private routing, permissions, or independent proof of deployment.

[Core concepts](01_core_frame.md) · [Reading rules](06_reading_rules.md)
