# DELETE /api/v4/projects/{id}/labels/{name}

**Resource:** [Labels](../resources/Labels.md)
**Delete an existing label**
**Operation ID:** `deleteApiV4ProjectsIdLabelsName`

This feature was added in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name or id of the label to be deleted |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

