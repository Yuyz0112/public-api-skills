# GET /api/v4/groups/{id}/epics/{eventable_id}/resource_state_events/{event_id}

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a single epic resource state event**
**Operation ID:** `getApiV4GroupsIdEpicsEventableIdResourceStateEventsEventId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `eventable_id` | path | integer | Yes | The ID of the epic |
| `event_id` | path | integer | Yes | The ID of a resource state event |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceStateEvent](../schemas/APIEntitiesResourceStateEvent/APIEntitiesResourceStateEvent.md)

