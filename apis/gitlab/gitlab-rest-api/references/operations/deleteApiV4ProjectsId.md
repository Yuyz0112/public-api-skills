# DELETE /api/v4/projects/{id}

**Resource:** [Projects](../resources/Projects.md)
**Delete a project**
**Operation ID:** `deleteApiV4ProjectsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 403 | Unauthenticated |
| 404 | Not found |

