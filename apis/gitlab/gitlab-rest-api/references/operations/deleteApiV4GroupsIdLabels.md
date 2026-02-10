# DELETE /api/v4/groups/{id}/labels

**Resource:** [Labels](../resources/Labels.md)
**Delete an existing label**
**Operation ID:** `deleteApiV4GroupsIdLabels`

This feature was added in GitLab 11.8 and deprecated in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `name` | query | string | Yes | The name of the label to be deleted |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

