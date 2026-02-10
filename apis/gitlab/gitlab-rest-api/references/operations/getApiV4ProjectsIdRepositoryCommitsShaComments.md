# GET /api/v4/projects/{id}/repository/commits/{sha}/comments

**Resource:** [Commits](../resources/Commits.md)
**Get a commit's comments**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsShaComments`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `sha` | path | string | Yes | A commit sha, or the name of a branch or tag |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommitNote](../schemas/APIEntitiesCommitNote/APIEntitiesCommitNote.md)

