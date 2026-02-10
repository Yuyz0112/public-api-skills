# POST /api/v4/projects/{id}/repository/commits

**Resource:** [Commits](../resources/Commits.md)
**Create a new commit**
**Operation ID:** `postApiV4ProjectsIdRepositoryCommits`

This feature was introduced in GitLab 8.13

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommitDetail](../schemas/APIEntitiesCommitDetail/APIEntitiesCommitDetail.md)

