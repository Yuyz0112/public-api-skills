# GET /api/v4/projects/{id}/repository/commits/{sha}/diff

**Resource:** [Commits](../resources/Commits.md)
**Get the diff for a specific commit of a project**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsShaDiff`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit sha, or the name of a branch or tag |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `unidiff` | query | boolean | No | A diff in a Unified diff format |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDiff](../schemas/APIEntitiesDiff/APIEntitiesDiff.md)

