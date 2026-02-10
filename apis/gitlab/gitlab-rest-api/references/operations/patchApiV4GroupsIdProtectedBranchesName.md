# PATCH /api/v4/groups/{id}/protected_branches/{name}

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Update a protected branch**
**Operation ID:** `patchApiV4GroupsIdProtectedBranchesName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |
| `name` | path | string | Yes | The name of the branch |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 ProtectedBranch Not Found |
| 422 | Push access levels access level has already been taken |

**Success Response Schema:**

[APIEntitiesGroupProtectedBranch](../schemas/APIEntitiesGroupProtectedBranch/APIEntitiesGroupProtectedBranch.md)

