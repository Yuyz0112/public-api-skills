# PUT /api/v4/hooks/{hook_id}/url_variables/{key}

**Resource:** [hooks](../resources/hooks.md)
**Set a url variable**
**Operation ID:** `putApiV4HooksHookIdUrlVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the hook |
| `key` | path | string | Yes | The key of the variable |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

