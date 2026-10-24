# Technical Guardrails — Historical Architecture Scope

This page lists a **reduced set of design constraints** from the earlier V7 architecture, not a platform-wide checklist that every public ToF Systems repository necessarily implements.

## Described constraints

- Docker-first operating direction.
- Postgres-only database direction within that private architecture.
- Explicit service and responsibility boundaries.
- Fail-closed thinking rather than silent bypasses.
- Trace- and provenance-aware processing.
- Platform-neutral internal logic with adapters at the edge.
- Language-model output late in the conceptual chain, not as the source of technical truth.

## How to interpret them

These items express **architectural intentions**. They do not, on their own, establish test coverage, operating status, or security guarantees. For example, the separate public Container Pulse tool deliberately works without a database.

Details of private security and operator controls are omitted. Consult the [public product overview](https://github.com/IMaugrenI/tof-showcase) and each repository's own documentation for verified dependencies and behavior.
