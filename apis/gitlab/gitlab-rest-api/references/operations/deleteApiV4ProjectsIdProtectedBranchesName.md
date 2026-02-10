# DELETE /api/v4/projects/{id}/protected_branches/{name}

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Unprotect a single branch**
**Operation ID:** `deleteApiV4ProjectsIdProtectedBranchesName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of the protected branch |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | 401 Unauthorized |
| 404 | 404 Project Not Found |

