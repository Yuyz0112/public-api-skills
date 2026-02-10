# GET /api/v4/projects/{id}/audit_events

**Resource:** [Projects](../resources/Projects.md)
**Get a list of audit events in this project.**
**Operation ID:** `getApiV4ProjectsIdAuditEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created_after` | query | string (date-time) | No | Return audit events created after the specified time |
| `created_before` | query | string (date-time) | No | Return audit events created before the specified time |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAuditEvent](../schemas/APIEntitiesAuditEvent/APIEntitiesAuditEvent.md)

