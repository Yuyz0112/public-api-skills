# GET /api/v4/projects/{id}/merge_requests/{eventable_id}/resource_state_events/{event_id}

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a single merge request resource state event**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsEventableIdResourceStateEventsEventId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `eventable_id` | path | integer | Yes | The IID of the merge request |
| `event_id` | path | integer | Yes | The ID of a resource state event |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceStateEvent](../schemas/APIEntitiesResourceStateEvent/APIEntitiesResourceStateEvent.md)

