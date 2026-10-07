# Architecture

This document defines how the AI should reason about software architecture.

## 1. Start with requirements

Architecture should begin with:

- Business objective.
- Functional requirements.
- Non-functional requirements.
- Constraints.
- Expected scale.
- Security requirements.

Do not choose technology before understanding the requirements.

## 2. Prefer appropriate simplicity

Use the simplest architecture that can reliably satisfy current and reasonably expected requirements.

Do not introduce distributed systems, microservices, complex infrastructure, or unnecessary abstractions without a clear reason.

## 3. Separation of concerns

Separate responsibilities so that changes in one area do not unnecessarily affect unrelated areas.

Consider separating:

- Presentation.
- Business logic.
- Data access.
- External integrations.
- Infrastructure.

The exact structure should depend on the project.

## 4. Design for change

Architecture should make likely future changes reasonably easy without prematurely building for hypothetical requirements.

Prioritize flexibility where change is actually expected.

## 5. Data

For important data, define:

- Source of truth.
- Ownership.
- Validation.
- Storage.
- Access patterns.
- Backup requirements.
- Security requirements.

## 6. External services

Treat external systems as unreliable dependencies.

Consider:

- Timeouts.
- Retries.
- Rate limits.
- Authentication.
- Failure handling.
- API changes.
- Monitoring.

## 7. Security by design

Security should be considered at the architectural level, not added only after implementation.

Protect:

- Credentials.
- User data.
- Business data.
- Internal systems.
- APIs.
- Administrative functionality.

## 8. Scalability

Do not optimize for massive scale before there is evidence that it is necessary.

First build a reliable system.

Scale the architecture when real usage, performance, cost, or business requirements justify it.

## 9. Architecture decisions

Important architectural decisions should record:

- Problem.
- Context.
- Options considered.
- Decision.
- Reason.
- Consequences.
- Alternatives rejected.

## 10. Review

Architecture should be reviewed when:

- Requirements change significantly.
- The system becomes difficult to maintain.
- Performance becomes a problem.
- Security risks emerge.
- Operational complexity becomes excessive.
