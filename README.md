# Software Development Lifecycle

The Software Development Lifecycle (SDLC) encompasses all processes, tools, and methodologies involved in planning, developing, testing, and delivering software from inception to retirement. Modern SDLC platforms integrate project planning, source control, code review, automated testing, security scanning, CI/CD pipelines, and release management into unified developer experience platforms. This profile covers the landscape of APIs, tools, and platforms that support each phase of the software development lifecycle.

**URL:** [Software Development Lifecycle](https://en.wikipedia.org/wiki/Software_development_process)

## Tags

- Software Engineering, Project Management, Quality Assurance, Development Process, DevOps, Platform Engineering

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### Planning and Tracking APIs
APIs for agile planning, backlog management, sprint tracking, roadmapping, and team capacity planning tools used in the planning phase of the software development lifecycle.

**Tags:** Agile Planning, Backlog Management, Sprint Tracking, Roadmapping

---

### Code and Review APIs
APIs for source control, code repositories, branching strategies, pull requests, and code review platforms that support collaborative development in the implementation phase.

**Human URL:** [Version Control](https://en.wikipedia.org/wiki/Version_control)

**Tags:** Source Control, Code Review, Version Control, Collaboration

#### Properties

- [Documentation](https://docs.github.com/en/rest)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json)

---

### Build and Test APIs
APIs for build automation, test frameworks, code coverage tools, and quality gates that verify software correctness and maintainability during the testing phase.

**Tags:** Build Automation, Testing, Code Coverage, Quality Gates

---

### Security Scanning APIs
APIs for SAST, DAST, software composition analysis, and container security scanning integrated into the development lifecycle.

**Tags:** SAST, DAST, Security Scanning, DevSecOps, SCA

---

### Deployment and Release APIs
APIs for CI/CD pipelines, infrastructure provisioning, environment management, feature flags, and progressive delivery tools.

**Tags:** CI/CD, Deployment, Infrastructure as Code, Feature Flags, Progressive Delivery

---

### Monitoring and Observability APIs
APIs for application performance monitoring, error tracking, log management, and distributed tracing supporting the operations and maintenance phase.

**Tags:** Monitoring, Observability, APM, Log Management, Tracing

---

### Developer Platform APIs
APIs for integrated developer experience platforms that unify planning, coding, building, testing, and deployment with internal developer portals and service catalogs.

**Tags:** Developer Platform, Internal Developer Portal, Service Catalog, Platform Engineering

---

## Common Resources

- [Software Development Process](https://en.wikipedia.org/wiki/Software_development_process)
- [Agile Software Development](https://en.wikipedia.org/wiki/Agile_software_development)
- [DevOps](https://en.wikipedia.org/wiki/DevOps)
- [DevSecOps](https://en.wikipedia.org/wiki/DevSecOps)
- [Platform Engineering](https://en.wikipedia.org/wiki/Platform_engineering)
- [Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration)
- [Continuous Delivery](https://en.wikipedia.org/wiki/Continuous_delivery)
- [Internal Developer Platform Guide](https://internaldeveloperplatform.org/)

## Artifacts

### JSON Schema

- [Sprint Schema](json-schema/software-development-lifecycle-sprint-schema.json) — Schema for agile sprints including capacity, velocity, and work item assignments
- [Deployment Schema](json-schema/software-development-lifecycle-deployment-schema.json) — Schema for deployment events including environment, strategy, and status

### JSON Structure

- [Sprint Structure](json-structure/software-development-lifecycle-sprint-structure.json) — Field-level documentation for the Sprint entity

### JSON-LD

- [SDLC Context](json-ld/software-development-lifecycle-context.jsonld) — JSON-LD context mapping SDLC vocabulary to schema.org and DOAP ontology terms

### Examples

- [Sprint Example](examples/software-development-lifecycle-sprint-example.json) — Sample active sprint with work items and progress metrics
- [Deployment Example](examples/software-development-lifecycle-deployment-example.json) — Sample successful blue-green production deployment

### Vocabulary

- [SDLC Vocabulary](vocabulary/software-development-lifecycle-vocabulary.yml) — Normative vocabulary covering lifecycle phases, DevOps practices, tooling, and DORA metrics

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
