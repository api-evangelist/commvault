# Commvault (commvault)
Commvault is a cloud-native cyber resilience platform that delivers unified data security, identity resilience, and cyber recovery. The Commvault REST API, Command Center API, and Automation API provide programmatic access to backup, restore, replication, threat scan, reporting, and orchestration capabilities across enterprise workloads spanning on-premises, virtual machines, and cloud applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - Backup, Cloud Storage, Cyber Recovery, Data Management, Data Protection, Disaster Recovery, Enterprise Software

## Timestamps

- **Created:** 2025-01-20
- **Modified:** 2026-04-28

## APIs

### Commvault REST API
The Commvault REST API provides programmatic access to Commvault data protection and management operations including authentication, clients, agents, subclients, backup and restore jobs, schedules, storage policies, and reporting. Authentication is token-based using a QSDK token issued by the Login operation, sent in the Authtoken header on subsequent calls.

**Human URL:** [https://documentation.commvault.com/v11/essential/rest_api_overview.html](https://documentation.commvault.com/v11/essential/rest_api_overview.html)

**Base URL:** `https://webserver.commvault.com/webconsole/api`

#### Tags

 - Backup, Clients, Data Management, Jobs, REST API, Restore, Subclients

#### Properties

- [Documentation](https://documentation.commvault.com/v11/essential/rest_api_overview.html)
- [Authentication](https://documentation.commvault.com/v11/essential/rest_api_authentication.html)
- [Postman Collection](https://documenter.getpostman.com/view/2046098/RW1aHzQg)
- [API Reference](https://api.commvault.com/swagger/)
- [OpenAPI](openapi/commvault-rest-openapi.yml)
- [Spectral Rules](rules/commvault-rules.yml)
- [Naftiko Capabilities](capabilities/commvault-backup-management.yml)

#### Features

- Token-based authentication via QSDK Authtoken header
- Client lifecycle (register, retrieve, update, retire)
- Subclient configuration for backup content and policies
- Backup and restore job execution
- Job monitoring and reporting
- Storage and schedule policy management
- Alerts and reporting

#### Use Cases

- Automated backup orchestration from CI/CD or runbooks
- Disaster recovery automation
- Cyber recovery integration with SOC and SIEM tooling
- Compliance and SLA reporting

### Commvault Command Center API
The Commvault Command Center API exposes the operations behind the modern web-based Command Center UI, providing centralized management, monitoring, dashboards, server group control, and workflow execution for Commvault environments.

**Human URL:** [https://documentation.commvault.com/2024/essential/command_center_overview.html](https://documentation.commvault.com/2024/essential/command_center_overview.html)

**Base URL:** `https://commandcenter.commvault.com/commandcenter/api`

#### Tags

 - Command Center, Dashboards, Management, Monitoring

#### Properties

- [Documentation](https://documentation.commvault.com/2024/essential/rest_api_command_center.html)
- [API Reference](https://api.commvault.com/)
- [OpenAPI](openapi/commvault-command-center-openapi.yml)
- [Spectral Rules](rules/commvault-rules.yml)
- [Naftiko Capabilities](capabilities/commvault-backup-management.yml)

### Commvault Automation API
The Commvault Automation API provides endpoints for executing Commvault Workflows, managing job scheduling, and orchestrating policy-driven operations across the protected estate. Workflows are reusable automation packages that combine REST calls, decision logic, and approvals.

**Human URL:** [https://documentation.commvault.com/v11/essential/automation_overview.html](https://documentation.commvault.com/v11/essential/automation_overview.html)

**Base URL:** `https://webserver.commvault.com/webconsole/api`

#### Tags

 - Automation, Orchestration, Scheduling, Workflows

#### Properties

- [Documentation](https://documentation.commvault.com/v11/essential/rest_api_automation.html)
- [OpenAPI](openapi/commvault-automation-openapi.yml)
- [Spectral Rules](rules/commvault-rules.yml)
- [Naftiko Capabilities](capabilities/commvault-backup-management.yml)

## Common Properties

- [Portal](https://cloud.commvault.com/)
- [Documentation](https://documentation.commvault.com/)
- [Support](https://www.commvault.com/support)
- [Login](https://login.commvault.com/)
- [Status](https://status.commvault.com/)
- [Blog](https://www.commvault.com/blogs)
- [Contact](https://www.commvault.com/contact-us)
- [Privacy Policy](https://www.commvault.com/privacy-policy)
- [Terms of Service](https://www.commvault.com/terms-of-use)
- [JSON-LD Context](json-ld/commvault-context.jsonld)
- [Backup Job JSON Schema](json-schema/commvault-backup-job-schema.json)
- [Client JSON Schema](json-schema/commvault-client-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
