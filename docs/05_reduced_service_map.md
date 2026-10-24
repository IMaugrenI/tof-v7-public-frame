# Service Boundaries — Reduced Public Model

This repository does not publish the complete private service map. Instead, the historical architecture reference highlights several design goals:

- Prefer **separate services with explicit responsibilities** to an undifferentiated monolith.
- Keep external platform protocols and adapters at the **system edge**.
- Keep current runtime state independent of symbolic identity or presentation.
- Distinguish audit records, current state, retention, and archive responsibilities.
- Preserve controlled transitions between areas of work.

This is a **conceptual relationship map**, not a list of active services, Docker containers, network routes, or deployed interfaces.

For concrete, runnable public projects, use the [ToF Systems showcase](https://github.com/IMaugrenI/tof-showcase); each tool documents its actual setup and functionality.
