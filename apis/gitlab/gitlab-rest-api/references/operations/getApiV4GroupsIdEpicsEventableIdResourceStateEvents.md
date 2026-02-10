# GET /api/v4/groups/{id}/epics/{eventable_id}/resource_state_events

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a list of epic resource state events**
**Operation ID:** `getApiV4GroupsIdEpicsEventableIdResourceStateEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `eventable_id` | path | integer | Yes | The ID of the epic |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceStateEvent](../schemas/APIEntitiesResourceStateEvent/APIEntitiesResourceStateEvent.md)

