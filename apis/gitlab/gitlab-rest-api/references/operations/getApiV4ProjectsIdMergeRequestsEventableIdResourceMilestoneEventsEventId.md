# GET /api/v4/projects/{id}/merge_requests/{eventable_id}/resource_milestone_events/{event_id}

**Resource:** [Resource events](../resources/Resource-events.md)
**Get single Merge request milestone event**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsEventableIdResourceMilestoneEventsEventId`

Returns a single milestone event for a specific project Merge request

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `event_id` | path | string | Yes | The ID of a resource milestone event |
| `eventable_id` | path | any | Yes | The ID of the eventable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesResourceMilestoneEvent](../schemas/APIEntitiesResourceMilestoneEvent/APIEntitiesResourceMilestoneEvent.md)

