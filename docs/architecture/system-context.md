# System Context

## Status

Not yet finalized.

This document will describe the system boundary and its relationship with external actors and systems after the product requirements have been sufficiently defined.

## Initial Concept

```text
                    ┌──────────────────────┐
                    │      Engineers       │
                    │  Leads / Architects  │
                    │      Managers        │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Engineering          │
                    │ Operations Platform   │
                    └──────────┬───────────┘
                               │
             ┌─────────────────┼─────────────────┐
             │                 │                 │
             ▼                 ▼                 ▼
          Source           Delivery          Runtime
          Systems          Systems           Systems
