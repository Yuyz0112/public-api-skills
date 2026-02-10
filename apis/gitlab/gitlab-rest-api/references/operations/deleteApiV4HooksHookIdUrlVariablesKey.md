# DELETE /api/v4/hooks/{hook_id}/url_variables/{key}

**Resource:** [hooks](../resources/hooks.md)
**Un-Set a url variable**
**Operation ID:** `deleteApiV4HooksHookIdUrlVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the hook |
| `key` | path | string | Yes | The key of the variable |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

