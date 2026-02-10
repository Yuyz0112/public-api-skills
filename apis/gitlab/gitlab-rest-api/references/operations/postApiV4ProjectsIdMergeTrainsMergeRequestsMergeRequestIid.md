# POST /api/v4/projects/{id}/merge_trains/merge_requests/{merge_request_iid}

**Resource:** [Merge trains](../resources/Merge-trains.md)
**Add a merge request to a merge train**
**Operation ID:** `postApiV4ProjectsIdMergeTrainsMergeRequestsMergeRequestIid`

This feature was introduced in GitLab 15.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 202 | Accepted |
| 400 | Failed to merge |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Conflict |

**Success Response Schema:**

[APIEntitiesMergeTrainsCar](../schemas/APIEntitiesMergeTrainsCar/APIEntitiesMergeTrainsCar.md)

