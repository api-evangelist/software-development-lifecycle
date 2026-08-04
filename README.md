# Software Development Lifecycle

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
