# GET /api/v4/projects/{id}/protected_branches/{name}

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Get a single protected branch**
**Operation ID:** `getApiV4ProjectsIdProtectedBranchesName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of the branch or wildcard |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 Project Not Found |

**Success Response Schema:**

[APIEntitiesProtectedBranch](../schemas/APIEntitiesProtectedBranch/APIEntitiesProtectedBranch.md)

