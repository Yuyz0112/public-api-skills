# GET /api/v4/projects/{id}/merge_trains/{target_branch}

**Resource:** [Merge trains](../resources/Merge-trains.md)
**Get the merge train for a project target branch**
**Operation ID:** `getApiV4ProjectsIdMergeTrainsTargetBranch`

This feature was introduced in Gitlab 15.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `target_branch` | path | string | Yes | The target branch of the merge request |
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

