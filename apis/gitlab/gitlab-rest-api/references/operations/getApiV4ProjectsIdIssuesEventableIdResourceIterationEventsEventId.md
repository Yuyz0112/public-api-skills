# GET /api/v4/projects/{id}/issues/{eventable_id}/resource_iteration_events/{event_id}

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a single issue resource iteration event**
**Operation ID:** `getApiV4ProjectsIdIssuesEventableIdResourceIterationEventsEventId`

This feature was introduced in GitLab 13.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path the project |
| `event_id` | path | string | Yes | The ID of a resource iteration event |
| `eventable_id` | path | any | Yes | The ID of the eventable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceIterationEvent](../schemas/APIEntitiesResourceIterationEvent/APIEntitiesResourceIterationEvent.md)

