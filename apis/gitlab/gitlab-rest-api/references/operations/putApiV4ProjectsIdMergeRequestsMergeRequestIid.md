# PUT /api/v4/projects/{id}/merge_requests/{merge_request_iid}

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Update merge request**
**Operation ID:** `putApiV4ProjectsIdMergeRequestsMergeRequestIid`

Updates an existing merge request. You can change the target branch, title, or even close the merge request.

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
| 404 | Not found |
| 409 | Conflict |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesMergeRequest](../schemas/APIEntitiesMergeRequest/APIEntitiesMergeRequest.md)

