# DELETE /api/v4/projects/{id}/share/{group_id}

**Resource:** [Projects](../resources/Projects.md)
**Remove a group share**
**Operation ID:** `deleteApiV4ProjectsIdShareGroupId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `group_id` | path | integer | Yes | The ID of the group |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 404 | Not found |

