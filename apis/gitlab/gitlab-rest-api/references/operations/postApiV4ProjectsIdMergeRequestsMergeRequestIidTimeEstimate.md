# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/time_estimate

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Set a time estimate for a merge_request**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidTimeEstimate`

Sets an estimated time of work for this merge_request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge_request. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssuableTimeStats](../schemas/APIEntitiesIssuableTimeStats/APIEntitiesIssuableTimeStats.md)

