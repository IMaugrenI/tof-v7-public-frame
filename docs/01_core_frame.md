# Architecture Reference — Core Concepts

This document explains the **system-boundary principles** recorded in the earlier ToF architecture stage labeled **V7**. The version number is retained for historical continuity; it is not a product name visitors need to learn.

## Core principles

- **Technical authority stays separate from expression.** Identity, wording, or symbols do not confer operating permissions.
- **Different spaces retain different responsibilities.** Planning, workbench material, archived records, governed references, and runtime state must not be silently merged.
- **Evidence and runtime state are not interchangeable.** A document describing intended behavior is not proof of active behavior.
- **Language-model output is not the authority source.** Generated text requires appropriate grounding and cannot independently approve actions.

## What the historical reference represents

The earlier V7 direction emphasized a controlled system architecture, clear internal boundaries, and deliberate continuation from previous work rather than unstructured feature accumulation.

It was **not** designed as just a bot/chat surface or a simple LLM wrapper. Equally, this public repository is **not** a complete implementation, full runtime release, or disclosure of private operating mechanics.

## Where to go next

[Space and responsibility boundaries](02_space_boundaries.md) · [Processing model](04_public_chain.md) · [Public project family](https://github.com/IMaugrenI/tof-showcase)
