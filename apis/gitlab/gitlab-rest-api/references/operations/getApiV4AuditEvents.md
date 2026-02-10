# GET /api/v4/audit_events

**Resource:** [Audit events](../resources/Audit-events.md)
**Get the list of audit events**
**Operation ID:** `getApiV4AuditEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `entity_type` | query | enum: Project, User, Group... | Yes | Return audit events for the specified entity type |
| `entity_id` | query | integer | No | Return audit events for the specified entity ID. If defined, the request must also include the `entity_type` attribute. |
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

