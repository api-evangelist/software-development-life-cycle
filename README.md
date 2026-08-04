# Software Development Life Cycle

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

The Software Development Life Cycle (SDLC) is a structured framework that defines the process for planning, creating, testing, and deploying high-quality software systems. It encompasses distinct phases including requirements analysis, system design, implementation, testing, deployment, and ongoing maintenance. Tools and platforms that support SDLC workflows provide capabilities for project management, source control, continuous integration and delivery, testing automation, release management, and collaboration across development teams.

**URL:** [Software Development Life Cycle](https://en.wikipedia.org/wiki/Software_development_life_cycle)

## Tags

- Software Engineering, Project Management, SDLC, Development Process, DevOps, CI/CD

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### Requirements Management APIs
APIs and tools for capturing, tracking, and managing software requirements throughout the development life cycle, including user stories, acceptance criteria, and traceability matrices.

**Human URL:** [Requirements Management](https://en.wikipedia.org/wiki/Requirements_management)

**Tags:** Requirements, User Stories, Backlog, Agile

---

### Source Control APIs
APIs for version control systems that manage code repositories, branches, commits, pull requests, and code reviews as part of the software development life cycle.

**Human URL:** [Version Control](https://en.wikipedia.org/wiki/Version_control)

**Tags:** Source Control, Version Control, Git, Repositories

#### Properties

- [Documentation](https://docs.github.com/en/rest)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json)

---

### Continuous Integration and Delivery APIs
APIs for CI/CD pipelines that automate the building, testing, and deployment of software changes, enabling frequent and reliable releases throughout the development life cycle.

**Human URL:** [CI/CD](https://en.wikipedia.org/wiki/CI/CD)

**Tags:** CI/CD, Continuous Integration, Continuous Delivery, Pipelines, Automation

---

### Testing and Quality Assurance APIs
APIs for automated testing frameworks and quality assurance platforms that support unit testing, integration testing, performance testing, and security testing throughout the SDLC.

**Human URL:** [Test Automation](https://en.wikipedia.org/wiki/Test_automation)

**Tags:** Testing, Quality Assurance, Test Automation, Security Testing

---

### Project Management APIs
APIs for project management and collaboration tools that track work items, sprints, milestones, and team velocity throughout the software development life cycle.

**Human URL:** [Software Project Management](https://en.wikipedia.org/wiki/Software_project_management)

**Tags:** Project Management, Agile, Scrum, Kanban, Sprint Planning

---

### Release Management APIs
APIs for managing software releases, deployments, and change management processes, ensuring controlled and auditable rollouts to production environments.

**Human URL:** [Software Release Life Cycle](https://en.wikipedia.org/wiki/Software_release_life_cycle)

**Tags:** Release Management, Deployment, Change Management, Versioning

---

## Common Resources

- [SDLC Wikipedia Article](https://en.wikipedia.org/wiki/Software_development_life_cycle)
- [Agile Software Development](https://en.wikipedia.org/wiki/Agile_software_development)
- [DevOps](https://en.wikipedia.org/wiki/DevOps)
- [Scrum Methodology](https://en.wikipedia.org/wiki/Scrum_(software_development))
- [Kanban Development](https://en.wikipedia.org/wiki/Kanban_(development))
- [Test-Driven Development](https://en.wikipedia.org/wiki/Test-driven_development)
- [Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration)
- [Continuous Delivery](https://en.wikipedia.org/wiki/Continuous_delivery)

## Artifacts

### JSON Schema

- [Work Item Schema](json-schema/software-development-life-cycle-work-item-schema.json) — Schema for work items (stories, tasks, bugs, epics) tracked throughout the SDLC
- [CI/CD Pipeline Schema](json-schema/software-development-life-cycle-pipeline-schema.json) — Schema for CI/CD pipeline definitions including stages, steps, and triggers

### JSON Structure

- [Work Item Structure](json-structure/software-development-life-cycle-work-item-structure.json) — Field-by-field structure documentation for the work item entity

### JSON-LD

- [SDLC Context](json-ld/software-development-life-cycle-context.jsonld) — JSON-LD context mapping SDLC vocabulary to schema.org and custom ontology terms

### Examples

- [Work Item Example](examples/software-development-life-cycle-work-item-example.json) — Sample work item representing a CI/CD configuration user story
- [Pipeline Example](examples/software-development-life-cycle-pipeline-example.json) — Sample CI/CD pipeline definition for a web API service

### Vocabulary

- [SDLC Vocabulary](vocabulary/software-development-life-cycle-vocabulary.yml) — Normative vocabulary covering SDLC phases, methodologies, artifacts, and quality dimensions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
