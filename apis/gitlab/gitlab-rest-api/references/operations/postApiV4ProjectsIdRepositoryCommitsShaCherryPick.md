# POST /api/v4/projects/{id}/repository/commits/{sha}/cherry_pick

**Resource:** [Commits](../resources/Commits.md)
**Cherry pick commit into a branch**
**Operation ID:** `postApiV4ProjectsIdRepositoryCommitsShaCherryPick`

This feature was introduced in GitLab 8.15

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit sha, or the name of a branch or tag to be cherry-picked |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommit](../schemas/APIEntitiesCommit/APIEntitiesCommit.md)

