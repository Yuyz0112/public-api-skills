# DELETE /api/v4/projects/{id}/labels

**Resource:** [Labels](../resources/Labels.md)
**Delete an existing label**
**Operation ID:** `deleteApiV4ProjectsIdLabels`

This feature was deprecated in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `label_id` | query | integer | No | The ID of the label to be deleted |
| `name` | query | string | No | The name of the label to be deleted |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

