# Product Problem

## Problem Statement

Engineering teams working on modern applications need information from multiple sources to understand an application, investigate issues, and make technical decisions.

This information is usually fragmented across different tools and systems.

Examples include:

- Product requirements
- Jira tickets
- Source repositories
- Pull requests
- Architecture documentation
- Architecture Decision Records
- API specifications
- Dependencies
- Deployment information
- Environment configuration
- Logs
- Metrics
- Traces
- Runtime health
- Test results

The engineer therefore has to manually reconstruct the context of the system before acting.

## Current Situation

A typical engineering investigation may require an engineer to move between several systems:

```text
Requirement
    ↓
Jira / Product Documentation
    ↓
Source Repository
    ↓
Architecture Documentation
    ↓
API / Dependency Information
    ↓
Deployment Information
    ↓
Runtime Monitoring
    ↓
Logs / Metrics / Traces
