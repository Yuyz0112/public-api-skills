# GET /api/v4/projects/{id}/issues/{eventable_id}/resource_weight_events/{event_id}

**Resource:** [Resource events](../resources/Resource-events.md)
**Get single issue weight event**
**Operation ID:** `getApiV4ProjectsIdIssuesEventableIdResourceWeightEventsEventId`

Returns a single weight event for a specific project issue

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `event_id` | path | string | Yes | The ID of a resource weight event |
| `eventable_id` | path | any | Yes | The ID of the eventable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesResourceWeightEvent](../schemas/APIEntitiesResourceWeightEvent/APIEntitiesResourceWeightEvent.md)

