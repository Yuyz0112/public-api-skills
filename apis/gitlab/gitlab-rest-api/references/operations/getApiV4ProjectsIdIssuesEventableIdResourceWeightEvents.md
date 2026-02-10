# GET /api/v4/projects/{id}/issues/{eventable_id}/resource_weight_events

**Resource:** [Resource events](../resources/Resource-events.md)
**List project issue weight events**
**Operation ID:** `getApiV4ProjectsIdIssuesEventableIdResourceWeightEvents`

Gets a list of all weight events for a single issue

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

[APIEntitiesResourceWeightEvent](../schemas/APIEntitiesResourceWeightEvent/APIEntitiesResourceWeightEvent.md)

