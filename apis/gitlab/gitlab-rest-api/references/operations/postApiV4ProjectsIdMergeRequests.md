# POST /api/v4/projects/{id}/merge_requests

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Create merge request**
**Operation ID:** `postApiV4ProjectsIdMergeRequests`

Create a new merge request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

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
| 409 | Conflict |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesMergeRequest](../schemas/APIEntitiesMergeRequest/APIEntitiesMergeRequest.md)

