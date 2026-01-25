# Audit log API

Asana's audit log is an immutable log of [important events](/docs/audit-log-events#supported-audit-log-events) in your organization's Asana instance.

The audit log API allows you to monitor and act upon important security and compliance-related changes. Organizations might use this API endpoint to:

* Set up proactive alerting with a Security Information and Event Management (SIEM) tool like [Splunk](https://asana.com/guide/help/api/splunk)
* Conduct reactive investigations when a security incident takes place
* Visualize key domain data in aggregate to identify security trends

Note that since the API provides insight into what is happening in an Asana instance, the data is [read-only](/reference/getauditlogevents). That is, there are no "write" or "update" endpoints for audit log events.

Only [Service Accounts](https://asana.com/guide/help/premium/service-accounts) in [Enterprise Domains](https://asana.com/enterprise) can access audit log API endpoints. Authentication with a Service Account's [personal access token](/docs/personal-access-token) is required.

For a full list of supported events, see [supported AuditLogEvents](/docs/audit-log-events#supported-audit-log-events).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/workspaces/{workspace_gid}/audit_log_events` | Get audit log events | [View](../operations/getAuditLogEvents.md) |
