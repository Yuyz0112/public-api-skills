# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/context_commits

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Create merge request context commits**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidContextCommits`

Create a list of merge request context commits.

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
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommit](../schemas/APIEntitiesCommit/APIEntitiesCommit.md)

