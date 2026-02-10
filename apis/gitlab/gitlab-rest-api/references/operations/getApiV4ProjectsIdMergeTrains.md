# GET /api/v4/projects/{id}/merge_trains

**Resource:** [Merge trains](../resources/Merge-trains.md)
**Get all merge trains of a project**
**Operation ID:** `getApiV4ProjectsIdMergeTrains`

This feature was introduced in GitLab 12.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `scope` | query | enum: active, complete | No | The scope of merge trains |
| `sort` | query | enum: asc, desc | No | Sort by asc (ascending) or desc (descending) |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeTrainsCar](../schemas/APIEntitiesMergeTrainsCar/APIEntitiesMergeTrainsCar.md)

