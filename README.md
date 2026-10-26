# Commvault (commvault)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Commvault is a cloud-native cyber resilience platform that delivers unified data security, identity resilience, and cyber recovery. The Commvault REST API, Command Center API, and Automation API provide programmatic access to backup, restore, replication, threat scan, reporting, and orchestration capabilities across enterprise workloads spanning on-premises, virtual machines, and cloud applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Backup
- Cloud Storage
- Cyber Recovery
- Data Management
- Data Protection
- Disaster Recovery
- Enterprise Software

## Timestamps

- **Created:** 2025-01-20
- **Modified:** 2026-05-19

## APIs

### Commvault REST API

The Commvault REST API provides programmatic access to Commvault data protection and management operations including authentication, clients, agents, subclients, backup and restore jobs, schedules, storage policies, and reporting. Authentication is token-based using a QSDK token issued by the Login operation, sent in the Authtoken header on subsequent calls.

- **Human URL:** [https://documentation.commvault.com/v11/essential/rest_api_overview.html](https://documentation.commvault.com/v11/essential/rest_api_overview.html)
- **Base URL:** `https://webserver.commvault.com/webconsole/api`

#### Tags

- Backup
- Clients
- Data Management
- Jobs
- REST API
- Restore
- Subclients

#### Properties

- [Documentation](https://documentation.commvault.com/v11/essential/rest_api_overview.html)
- [Authentication](https://documentation.commvault.com/v11/essential/rest_api_authentication.html)
- [Postman  Collection](https://documenter.getpostman.com/view/2046098/RW1aHzQg)
- [API Reference](https://api.commvault.com/swagger/)
- [OpenAPI](openapi/commvault-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commvault-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commvault-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/commvault-rules.yml)

### Commvault Command Center API

The Commvault Command Center API exposes the operations behind the modern web-based Command Center UI, providing centralized management, monitoring, dashboards, server group control, and workflow execution for Commvault environments.

- **Human URL:** [https://documentation.commvault.com/2024/essential/command_center_overview.html](https://documentation.commvault.com/2024/essential/command_center_overview.html)
- **Base URL:** `https://commandcenter.commvault.com/commandcenter/api`

#### Tags

- Command Center
- Dashboards
- Management
- Monitoring

#### Properties

- [Documentation](https://documentation.commvault.com/2024/essential/rest_api_command_center.html)
- [API Reference](https://api.commvault.com/)
- [OpenAPI](openapi/commvault-command-center-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commvault-command-center.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commvault-command-center.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/commvault-rules.yml)

### Commvault Automation API

The Commvault Automation API provides endpoints for executing Commvault Workflows, managing job scheduling, and orchestrating policy-driven operations across the protected estate. Workflows are reusable automation packages that combine REST calls, decision logic, and approvals.

- **Human URL:** [https://documentation.commvault.com/v11/essential/automation_overview.html](https://documentation.commvault.com/v11/essential/automation_overview.html)
- **Base URL:** `https://webserver.commvault.com/webconsole/api`

#### Tags

- Automation
- Orchestration
- Scheduling
- Workflows

#### Properties

- [Documentation](https://documentation.commvault.com/v11/essential/rest_api_automation.html)
- [OpenAPI](openapi/commvault-automation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commvault-automation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commvault-automation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/commvault-rules.yml)

## Common Properties

- [GitHub Organization](https://github.com/Commvault)
- [LinkedIn](https://www.linkedin.com/company/commvault)
- [Portal](https://cloud.commvault.com/)
- [Documentation](https://documentation.commvault.com/)
- [Support](https://www.commvault.com/support)
- [Login](https://login.commvault.com/)
- [Status Page](https://status.commvault.com/)
- [Blog](https://www.commvault.com/blogs)
- [Contact](https://www.commvault.com/contact-us)
- [Privacy Policy](https://www.commvault.com/privacy-policy)
- [Terms of Service](https://www.commvault.com/terms-of-use)
- [JSON-LD](json-ld/commvault-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/commvault-backup-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/commvault-client-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
