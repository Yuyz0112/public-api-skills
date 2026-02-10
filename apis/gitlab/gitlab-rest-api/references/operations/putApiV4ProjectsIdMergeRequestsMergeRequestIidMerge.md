# PUT /api/v4/projects/{id}/merge_requests/{merge_request_iid}/merge

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Merge a merge request**
**Operation ID:** `putApiV4ProjectsIdMergeRequestsMergeRequestIidMerge`

Accept and merge changes submitted with the merge request using this API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |
| 405 | Method not allowed |
| 409 | Conflict |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesMergeRequest](../schemas/APIEntitiesMergeRequest/APIEntitiesMergeRequest.md)

