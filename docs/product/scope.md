# Product Scope

## Purpose

This document defines what belongs inside and outside the current product scope.

Scope will evolve as requirements become clearer.

---

# MVP

The MVP is expected to establish a useful engineering context around an application.

Candidate capabilities:

- Application registry
- Application metadata
- Application ownership
- Application features
- Requirements
- Architecture decisions
- Dependencies
- Environments
- Basic runtime health

The final MVP will be determined from validated requirements.

---

# Potential Future Capabilities

These are intentionally not MVP commitments.

- GitHub integration
- Jira integration
- CI/CD integration
- Runtime telemetry ingestion
- Automated dependency discovery
- Engineering analytics
- AI-assisted engineering context
- Architecture recommendations
- Anomaly detection
- Operational intelligence

---

# Explicitly Out of Scope Initially

The following should not be implemented merely to demonstrate technology:

- Microservices
- Microfrontends
- Kafka/event streaming
- Redis
- Kubernetes
- Service mesh
- Complex caching infrastructure
- Multi-region deployment
- Event sourcing
- CQRS
- AI chatbot

Each of these technologies may become relevant later if a concrete requirement justifies it.

---

# Scope Decision Rule

A feature enters the scope only when:

```text
User problem
      ↓
Requirement
      ↓
Value
      ↓
Constraint
      ↓
Implementation decision
