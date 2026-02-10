# GET /api/v4/projects/{id}/issues/{eventable_id}/resource_iteration_events

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a list of issue resource iteration events**
**Operation ID:** `getApiV4ProjectsIdIssuesEventableIdResourceIterationEvents`

This feature was introduced in GitLab 13.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path the project |
| `eventable_id` | path | any | Yes | The ID of the eventable |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceIterationEvent](../schemas/APIEntitiesResourceIterationEvent/APIEntitiesResourceIterationEvent.md)

