# GET /api/v4/projects/{id}/repository/commits/{sha}/merge_requests

**Resource:** [Commits](../resources/Commits.md)
**Get Merge Requests associated with a commit**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsShaMergeRequests`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit sha, or the name of a branch or tag on which to find Merge Requests |
| `state` | query | string | No | Filter merge-requests by state |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeRequestBasic](../schemas/APIEntitiesMergeRequestBasic/APIEntitiesMergeRequestBasic.md)

