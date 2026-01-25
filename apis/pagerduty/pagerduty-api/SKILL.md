---
name: pagerduty-api
description: This document describes the PagerDuty REST APIs.. Use when working with the PagerDuty API or when the user needs to interact with this API.
metadata:
  api-version: "2.0.0"
  openapi-version: "3.0.2"
  contact: "support@pagerduty.com"
---

# PagerDuty API

This document describes the PagerDuty REST APIs.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 40 resource index files
├── operations/     # 390 operation detail files
└── schemas/        # 89 schema groups, 244 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://api.pagerduty.com` - PagerDuty V2 API.

## Authentication

Supported methods: **api_key**. See `references/authentication.md` for details.

## Resources

- **Event Orchestrations** → `references/resources/Event-Orchestrations.md` (39 ops) - Event Orchestrations allow you to route events to 
- **Users** → `references/resources/Users.md` (35 ops) - Users are members of a PagerDuty account that have
- **Incidents** → `references/resources/Incidents.md` (28 ops) - An incident represents a problem or an issue that 
- **Status Pages** → `references/resources/Status-Pages.md` (27 ops) - Status Pages can be public or private read-only pa
- **Automation Actions** → `references/resources/Automation-Actions.md` (25 ops) - Automation Actions invoke jobs that are staged in 
- **Services** → `references/resources/Services.md` (19 ops) - A Service may represent an application, component,
- **Analytics** → `references/resources/Analytics.md` (16 ops) - Provides enriched incident data.

- **Business Services** → `references/resources/Business-Services.md` (16 ops) - Business services model capabilities that span mul
- **Incident Workflows** → `references/resources/Incident-Workflows.md` (15 ops) - An Incident Workflow is a sequence of configurable
- **Incident Types** → `references/resources/Incident-Types.md` (14 ops) - Incident Types are a feature which will allow cust
- **Teams** → `references/resources/Teams.md` (14 ops) - A team is a collection of Users and Escalation Pol
- **Webhooks** → `references/resources/Webhooks.md` (12 ops) - A webhook is a way to receive events that occur on
- **Schedules** → `references/resources/Schedules.md` (11 ops) - A Schedule determines the time periods that users 
- **Rulesets** → `references/resources/Rulesets.md` (10 ops) - Rulesets allow you to route events to an endpoint 
- **Service Custom Fields** → `references/resources/Service-Custom-Fields.md` (10 ops) - Custom fields allow you to enrich PagerDuty servic
- **Incident Custom Fields** → `references/resources/Incident-Custom-Fields.md` (9 ops) - Custom fields allow you to enrich PagerDuty incide
- **Workflow Integrations** → `references/resources/Workflow-Integrations.md` (8 ops) - Workflow Integrations are a way to connect PagerDu
- **Tags** → `references/resources/Tags.md` (7 ops) - A Tag is applied to Escalation Policies, Teams or 
- **Templates** → `references/resources/Templates.md` (7 ops) - Templates is a new feature which will allow custom
- **Change Events** → `references/resources/Change-Events.md` (6 ops) - Change Events enable you to send informational eve
- **Escalation Policies** → `references/resources/Escalation-Policies.md` (6 ops) - Escalation policies define which user should be al
- **Extensions** → `references/resources/Extensions.md` (6 ops) - Extensions are representations of Extension Schema
- **Add-ons** → `references/resources/Add-ons.md` (5 ops) - Developers can write their own functionality to in
- **Alert Grouping Settings** → `references/resources/Alert-Grouping-Settings.md` (5 ops) - Alert Grouping Settings allow you to configure how
- **Maintenance Windows** → `references/resources/Maintenance-Windows.md` (5 ops) - A Maintenance Window is used to temporarily disabl
- **Status Dashboards** → `references/resources/Status-Dashboards.md` (5 ops) - Status Dashboards represent user-defined views for
- **Service Dependencies** → `references/resources/Service-Dependencies.md` (4 ops) - Services are categorized into technical and busine
- **Standards** → `references/resources/Standards.md` (4 ops) - Standards help provide a clear understanding of wh
- **Log Entries** → `references/resources/Log-Entries.md` (3 ops) - A log of all the events that happen to an Incident
- **Session Configurations** → `references/resources/Session-Configurations.md` (3 ops)
- **Abilities** → `references/resources/Abilities.md` (2 ops) - This describes your account's abilities by feature
- **Extension Schemas** → `references/resources/Extension-Schemas.md` (2 ops) - A PagerDuty extension vendor represents a specific
- **Licenses** → `references/resources/Licenses.md` (2 ops) - Licenses are allocated to Users to allow for per-U
- **OAuth Delegations** → `references/resources/OAuth-Delegations.md` (2 ops)
- **Paused Incident Reports** → `references/resources/Paused-Incident-Reports.md` (2 ops) - Provides paused Incident reporting data on service
- **Vendors** → `references/resources/Vendors.md` (2 ops) - A PagerDuty Vendor represents a specific type of i
- **Audit** → `references/resources/Audit.md` (1 ops) - Provides audit record data.

- **Notifications** → `references/resources/Notifications.md` (1 ops) - A Notification is created when an Incident is trig
- **On-Calls** → `references/resources/On-Calls.md` (1 ops) - An on-call represents a contiguous unit of time fo
- **Priorities** → `references/resources/Priorities.md` (1 ops) - A priority is a label representing the importance 
