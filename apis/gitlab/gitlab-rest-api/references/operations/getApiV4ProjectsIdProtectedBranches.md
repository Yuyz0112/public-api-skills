# GET /api/v4/projects/{id}/protected_branches

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Get a project's protected branches**
**Operation ID:** `getApiV4ProjectsIdProtectedBranches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `search` | query | string | No | Search for a protected branch by name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 Project Not Found |

**Success Response Schema:**

[APIEntitiesProtectedBranch](../schemas/APIEntitiesProtectedBranch/APIEntitiesProtectedBranch.md)

