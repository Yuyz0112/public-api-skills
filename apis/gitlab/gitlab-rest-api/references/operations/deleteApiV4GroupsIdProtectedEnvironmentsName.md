# DELETE /api/v4/groups/{id}/protected_environments/{name}

**Resource:** [Protected environments](../resources/Protected-environments.md)
**Unprotect a single environment**
**Operation ID:** `deleteApiV4GroupsIdProtectedEnvironmentsName`

This feature was introduced in GitLab 14.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group maintained by the authenticated user |
| `name` | path | string | Yes | The tier name of the protected environment |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

