# GET /api/v4/groups/{id}/protected_branches/{name}

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Get a single protected branch**
**Operation ID:** `getApiV4GroupsIdProtectedBranchesName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |
| `name` | path | string | Yes | The name of the branch or wildcard |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 ProtectedBranch Not Found |

**Success Response Schema:**

[APIEntitiesGroupProtectedBranch](../schemas/APIEntitiesGroupProtectedBranch/APIEntitiesGroupProtectedBranch.md)

