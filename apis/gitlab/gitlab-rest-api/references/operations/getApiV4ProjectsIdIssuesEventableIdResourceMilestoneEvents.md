# GET /api/v4/projects/{id}/issues/{eventable_id}/resource_milestone_events

**Resource:** [Resource events](../resources/Resource-events.md)
**List project Issue milestone events**
**Operation ID:** `getApiV4ProjectsIdIssuesEventableIdResourceMilestoneEvents`

Gets a list of all milestone events for a single Issue

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `eventable_id` | path | any | Yes | The ID of the eventable |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceMilestoneEvent](../schemas/APIEntitiesResourceMilestoneEvent/APIEntitiesResourceMilestoneEvent.md)

