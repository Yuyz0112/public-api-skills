# POST /api/v4/projects/{id}/repository/commits/{sha}/comments

**Resource:** [Commits](../resources/Commits.md)
**Post comment to commit**
**Operation ID:** `postApiV4ProjectsIdRepositoryCommitsShaComments`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit sha, or the name of a branch or tag on which to post a comment |

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

[APIEntitiesCommitNote](../schemas/APIEntitiesCommitNote/APIEntitiesCommitNote.md)

