# POST /api/v4/projects/{id}/protected_branches

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Protect a single branch**
**Operation ID:** `postApiV4ProjectsIdProtectedBranches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | 401 Unauthorized |
| 404 | 404 Project Not Found |
| 409 | Protected branch 'main' already exists |
| 422 | name is missing |

**Success Response Schema:**

[APIEntitiesProtectedBranch](../schemas/APIEntitiesProtectedBranch/APIEntitiesProtectedBranch.md)

