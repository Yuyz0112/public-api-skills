# GET /api/v4/groups/{id}/audit_events

**Resource:** [Audit events](../resources/Audit-events.md)
**Get a list of audit events in this group.**
**Operation ID:** `getApiV4GroupsIdAuditEvents`

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

