# GET /api/v4/projects/{id}/repository/commits/{sha}/refs

**Resource:** [Commits](../resources/Commits.md)
**Get all references a commit is pushed to**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsShaRefs`

This feature was introduced in GitLab 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | path | string | Yes | A commit sha |
| `type` | query | enum: branch, tag, all | No | Scope |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesBasicRef](../schemas/APIEntitiesBasicRef/APIEntitiesBasicRef.md)

