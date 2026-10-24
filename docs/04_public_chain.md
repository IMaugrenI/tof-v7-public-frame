# Processing Model — Reduced Public View

This architecture reference intentionally does **not** publish a complete runtime chain. The following sequence retains broad areas from the earlier V7 processing model:

1. **Ingress / edge perception:** accept external input through defined interfaces.
2. **Gate / governance checks:** establish admission and authorization context.
3. **Safety / analysis:** apply relevant checks and interpret accepted material.
4. **Workers / state / retention:** perform bounded work while distinguishing live state and retained records.
5. **Archive / vector / LLM / output:** maintain later evidence, retrieval, generation, and presentation roles.

The grouping is **illustrative**. It does not claim exactly five deployed services, a fixed order for every request, or that all functions have been publicly demonstrated.

The essential distinction is that language-model output comes after controlled input handling in the described approach. It is **not** itself the truth core or authorization authority.

[Core concepts](01_core_frame.md) · [Service boundaries](05_reduced_service_map.md)
