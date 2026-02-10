# GET /api/v4/groups/{id}/epics/{eventable_id}/resource_label_events/{event_id}

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a single epic resource label event**
**Operation ID:** `getApiV4GroupsIdEpicsEventableIdResourceLabelEventsEventId`

This feature was introduced in 11.3

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `event_id` | path | string | Yes | The ID of a resource label event |
| `eventable_id` | path | any | Yes | The ID of the epic |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceLabelEvent](../schemas/APIEntitiesResourceLabelEvent/APIEntitiesResourceLabelEvent.md)

