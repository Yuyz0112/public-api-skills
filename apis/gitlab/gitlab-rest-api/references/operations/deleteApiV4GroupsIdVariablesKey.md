# DELETE /api/v4/groups/{id}/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Delete an existing variable from a group**
**Operation ID:** `deleteApiV4GroupsIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group or URL-encoded path of the group owned by the authenticated
      user |
| `key` | path | string | Yes | The key of a variable |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 404 | Group Variable Not Found |

