# DELETE /api/v4/groups/{id}/labels/{name}

**Resource:** [Labels](../resources/Labels.md)
**Delete an existing label**
**Operation ID:** `deleteApiV4GroupsIdLabelsName`

This feature was added in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `name` | path | string | Yes | The name or id of the label to be deleted |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

