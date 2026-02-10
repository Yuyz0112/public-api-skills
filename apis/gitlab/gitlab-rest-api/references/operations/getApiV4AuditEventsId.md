# GET /api/v4/audit_events/{id}

**Resource:** [Audit events](../resources/Audit-events.md)
**Get single audit event**
**Operation ID:** `getApiV4AuditEventsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of audit event |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAuditEvent](../schemas/APIEntitiesAuditEvent/APIEntitiesAuditEvent.md)

