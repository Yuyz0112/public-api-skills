# GET /api/v4/projects/{id}/events

**Resource:** [Events](../resources/Events.md)
**List a project's visible events**
**Operation ID:** `getApiV4ProjectsIdEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `action` | query | string | No | Event action to filter on |
| `target_type` | query | enum: issue, milestone, merge_request... | No | Event target type to filter on |
| `before` | query | string (date) | No | Include only events created before this date |
| `after` | query | string (date) | No | Include only events created after this date |
| `sort` | query | enum: asc, desc | No | Return events sorted in ascending and descending order |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesEvent](../schemas/APIEntitiesEvent/APIEntitiesEvent.md)

