# POST /api/v4/groups/{id}/protected_branches

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Protect a single branch**
**Operation ID:** `postApiV4GroupsIdProtectedBranches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | 401 Unauthorized |
| 404 | 404 Group Not Found |
| 409 | Protected branch 'main' already exists |
| 422 | name is missing |

**Success Response Schema:**

[APIEntitiesGroupProtectedBranch](../schemas/APIEntitiesGroupProtectedBranch/APIEntitiesGroupProtectedBranch.md)

