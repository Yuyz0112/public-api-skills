# GET /api/v4/projects/{id}/merge_trains/merge_requests/{merge_request_iid}

**Resource:** [Merge trains](../resources/Merge-trains.md)
**Get the status of a merge request on a merge train**
**Operation ID:** `getApiV4ProjectsIdMergeTrainsMergeRequestsMergeRequestIid`

This feature was introduced in Gitlab 15.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeTrainsCar](../schemas/APIEntitiesMergeTrainsCar/APIEntitiesMergeTrainsCar.md)

