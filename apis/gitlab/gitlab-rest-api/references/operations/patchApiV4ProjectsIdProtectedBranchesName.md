# PATCH /api/v4/projects/{id}/protected_branches/{name}

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Update a protected branch**
**Operation ID:** `patchApiV4ProjectsIdProtectedBranchesName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of the branch |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 404 | 404 Project Not Found |
| 422 | Push access levels access level has already been taken |

**Success Response Schema:**

[APIEntitiesProtectedBranch](../schemas/APIEntitiesProtectedBranch/APIEntitiesProtectedBranch.md)

