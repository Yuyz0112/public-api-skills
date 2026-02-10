# DELETE /api/v4/projects/{id}/fork

**Resource:** [Projects](../resources/Projects.md)
**Remove a forked_from relationship**
**Operation ID:** `deleteApiV4ProjectsIdFork`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 304 | Not modified |
| 403 | Unauthenticated |
| 404 | Not found |

