# Ledgr — Company Context

## Company

**Ledgr** is a fictional UK B2B fintech API company providing integration services that help financial institutions connect to UK banking infrastructure.

Ledgr exists solely to provide realistic organisational and technical context for the platform. The project focuses on the internal developer platform rather than implementing real financial services.

## Engineering Organisation

Ledgr has approximately **20 engineers** organised across:

* Product Squad Alpha
* Product Squad Bravo
* Product Squad Charlie
* Platform Team

Product squads own and operate their applications. The Platform Team provides shared infrastructure, delivery capabilities and engineering standards that allow those squads to deploy and operate services consistently.

## Platform Objective

Enable product teams to deliver services quickly through a standardised, self-service platform that provides secure defaults, operational visibility and consistent delivery workflows.

## Engineering Challenges

The platform is intended to address several common problems as the engineering organisation grows:

* Inconsistent service delivery patterns between product squads
* Environment and configuration drift
* Excessive manual processes
* Infrastructure knowledge duplicated across squads
* Limited self-service for routine engineering tasks

## Scope

The initial platform deliberately targets a small engineering organisation and prioritises learning and demonstrating core platform engineering capabilities.

The initial scope is limited to:

* A single Kubernetes cluster
* A maximum of three representative application services
* A single primary golden path for application delivery
* No multi-region architecture
* No real banking or payment-rail integrations
* Platform capabilities rather than complex business functionality

Additional complexity will only be introduced where it demonstrates a meaningful platform engineering capability or addresses a limitation encountered during implementation.
