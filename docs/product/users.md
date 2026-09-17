# Users

## Primary Users

### 1. Software Engineer

The software engineer uses the platform to understand an application or feature before implementing changes or investigating problems.

Typical questions:

- What is this application responsible for?
- What are its dependencies?
- What requirements does this feature satisfy?
- What architecture decisions affect this area?
- What changed recently?
- Is the system currently healthy?

### 2. Technical Lead / Architect

The technical lead or architect uses the platform to understand system boundaries, dependencies, architectural decisions, and operational characteristics.

Typical questions:

- What systems depend on this application?
- Why was a particular architecture chosen?
- What are the important constraints?
- Where are the major dependencies?
- What are the known operational risks?
- How has the architecture evolved?

### 3. Engineering Manager

The engineering manager uses the platform to understand the engineering landscape and identify areas requiring attention.

Typical questions:

- Which applications are healthy?
- Which applications have recurring operational issues?
- Where is technical debt accumulating?
- Which systems have important dependencies?
- What engineering risks require attention?

## Secondary Users

Potential future users include:

- QA engineers
- Product managers
- Site reliability engineers
- Platform engineers
- Support engineers
- Security engineers

These personas will only become product requirements if validated as part of the product discovery process.

## User Context

The platform should not assume that every user needs the same level of information.

For example:

```text
Engineer
    → Feature
    → Requirements
    → Code
    → Dependencies
    → Runtime behaviour

Architect
    → System boundaries
    → Dependencies
    → Architecture decisions
    → Reliability
    → Security

Engineering Manager
    → Application landscape
    → Health
    → Risk
    → Delivery / operational trends
