# GET /api/v4/projects/{id}/repository/merge_base

**Resource:** [Repositories](../resources/Repositories.md)
**Get the common ancestor between commits**
**Operation ID:** `getApiV4ProjectsIdRepositoryMergeBase`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `refs` | query | any | Yes | The refs to find the common ancestor of, multiple refs can be passed |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesCommit](../schemas/APIEntitiesCommit/APIEntitiesCommit.md)

