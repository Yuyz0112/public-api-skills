# GET /api/v4/projects/{id}/repository/commits/{sha}/sequence

**Resource:** [Commits](../resources/Commits.md)
**Get the sequence count of a commit SHA**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsShaSequence`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit SHA |
| `first_parent` | query | boolean | No | Only include the first parent of merges |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommitSequence](../schemas/APIEntitiesCommitSequence/APIEntitiesCommitSequence.md)

