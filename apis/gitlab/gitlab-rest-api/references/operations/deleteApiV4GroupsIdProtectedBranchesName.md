# DELETE /api/v4/groups/{id}/protected_branches/{name}

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Unprotect a single branch**
**Operation ID:** `deleteApiV4GroupsIdProtectedBranchesName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |
| `name` | path | string | Yes | The name of the protected branch |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | 401 Unauthorized |
| 404 | 404 ProtectedBranch Not Found |

