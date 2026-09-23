# ADR-001: Local Kubernetes Environment

## Status
Accepted

## Context
The platform requires a local Kubernetes environment for development and
learning before introducing cloud-hosted Kubernetes.

The environment should be inexpensive, reproducible, lightweight and
sufficient for deploying workloads and introducing GitOps with Argo CD.

## Decision
Use kind for the initial local Kubernetes environment.

## Alternatives Considered

### k3d / k3s
Lightweight and well suited to local development, but introduces k3s-specific
packaging and defaults that are unnecessary for the initial learning objectives.

### Cloud-managed Kubernetes
More representative of a production environment, but introduces cost and
cloud-specific complexity before Kubernetes fundamentals have been established.

## Consequences
- Kubernetes can run locally using Docker.
- Clusters can be created and destroyed cheaply and repeatedly.
- Initial development is not representative of all aspects of a managed
  production Kubernetes service.
- Cloud deployment can be introduced later without changing the platform's
  core Kubernetes concepts.