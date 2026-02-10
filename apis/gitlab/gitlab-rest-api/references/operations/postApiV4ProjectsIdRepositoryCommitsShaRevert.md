# POST /api/v4/projects/{id}/repository/commits/{sha}/revert

**Resource:** [Commits](../resources/Commits.md)
**Revert a commit in a branch**
**Operation ID:** `postApiV4ProjectsIdRepositoryCommitsShaRevert`

This feature was introduced in GitLab 11.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | Commit SHA to revert |

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

