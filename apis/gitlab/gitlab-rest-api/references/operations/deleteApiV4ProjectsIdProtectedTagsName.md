# DELETE /api/v4/projects/{id}/protected_tags/{name}

**Resource:** [Protected tags](../resources/Protected-tags.md)
**Unprotect a single tag**
**Operation ID:** `deleteApiV4ProjectsIdProtectedTagsName`

This feature was introduced in GitLab 11.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of the protected tag |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Unauthenticated |
| 404 | Not found |
| 412 | Precondition Failed |

