# GET /api/v4/projects/{id}/issues/{eventable_id}/resource_label_events

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a list of issue resource label events**
**Operation ID:** `getApiV4ProjectsIdIssuesEventableIdResourceLabelEvents`

This feature was introduced in 11.3

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `eventable_id` | path | any | Yes | The IID of the issue |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceLabelEvent](../schemas/APIEntitiesResourceLabelEvent/APIEntitiesResourceLabelEvent.md)

