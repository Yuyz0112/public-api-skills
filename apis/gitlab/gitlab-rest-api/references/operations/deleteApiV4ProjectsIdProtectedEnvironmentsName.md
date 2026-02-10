# DELETE /api/v4/projects/{id}/protected_environments/{name}

**Resource:** [Protected environments](../resources/Protected-environments.md)
**Unprotect a single environment**
**Operation ID:** `deleteApiV4ProjectsIdProtectedEnvironmentsName`

Unprotects the given protected environment. This feature was introduced in GitLab 12.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `name` | path | string | Yes | The name of the protected environment |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

