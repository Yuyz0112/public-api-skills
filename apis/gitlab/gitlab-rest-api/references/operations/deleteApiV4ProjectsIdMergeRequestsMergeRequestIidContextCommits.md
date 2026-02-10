# DELETE /api/v4/projects/{id}/merge_requests/{merge_request_iid}/context_commits

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Delete merge request context commits**
**Operation ID:** `deleteApiV4ProjectsIdMergeRequestsMergeRequestIidContextCommits`

Delete a list of merge request context commits.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `commits` | query | any | Yes | The context commits’ SHA. |

## Responses

| Status | Description |
|--------|-------------|
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

