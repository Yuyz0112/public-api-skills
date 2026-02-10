# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/context_commits

**Resource:** [Merge requests](../resources/Merge-requests.md)
**List merge request context commits**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidContextCommits`

Get a list of merge request context commits.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommit](../schemas/APIEntitiesCommit/APIEntitiesCommit.md)

