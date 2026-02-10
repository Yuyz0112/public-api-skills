# GET /api/v4/projects/{id}/repository/compare

**Resource:** [Repositories](../resources/Repositories.md)
**Compare two branches, tags, or commits**
**Operation ID:** `getApiV4ProjectsIdRepositoryCompare`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `from` | query | string | Yes | The commit, branch name, or tag name to start comparison |
| `to` | query | string | Yes | The commit, branch name, or tag name to stop comparison |
| `from_project_id` | query | integer | No | The project to compare from |
| `straight` | query | boolean | No | Comparison method, `true` for direct comparison between `from` and `to` (`from`..`to`), `false` to compare using merge base (`from`...`to`) |
| `unidiff` | query | boolean | No | A diff in a Unified diff format |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesCompare](../schemas/APIEntitiesCompare/APIEntitiesCompare.md)

