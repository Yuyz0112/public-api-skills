# GET /api/v4/groups/{id}/audit_events/{audit_event_id}

**Resource:** [Groups](../resources/Groups.md)
**Get a specific audit event in this group.**
**Operation ID:** `getApiV4GroupsIdAuditEventsAuditEventId`

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

