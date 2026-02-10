# GET /api/v4/projects/{id}/repository/commits/{sha}

**Resource:** [Commits](../resources/Commits.md)
**Get a specific commit of a project**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsSha`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit sha, or the name of a branch or tag |
| `stats` | query | boolean | No | Include commit stats |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommitDetail](../schemas/APIEntitiesCommitDetail/APIEntitiesCommitDetail.md)

