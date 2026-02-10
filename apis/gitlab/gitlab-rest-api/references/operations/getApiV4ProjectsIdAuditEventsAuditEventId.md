# GET /api/v4/projects/{id}/audit_events/{audit_event_id}

**Resource:** [Projects](../resources/Projects.md)
**Get a specific audit event in this project.**
**Operation ID:** `getApiV4ProjectsIdAuditEventsAuditEventId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `audit_event_id` | path | integer | Yes | The ID of the audit event |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAuditEvent](../schemas/APIEntitiesAuditEvent/APIEntitiesAuditEvent.md)

