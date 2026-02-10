# GET /api/v4/projects/{id}/repository/commits/{sha}/signature

**Resource:** [Commits](../resources/Commits.md)
**Get a commit's signature**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsShaSignature`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit sha, or the name of a branch or tag |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommitSignature](../schemas/APIEntitiesCommitSignature/APIEntitiesCommitSignature.md)

