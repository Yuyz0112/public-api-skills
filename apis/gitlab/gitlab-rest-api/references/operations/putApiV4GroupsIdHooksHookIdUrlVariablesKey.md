# PUT /api/v4/groups/{id}/hooks/{hook_id}/url_variables/{key}

**Resource:** [groups](../resources/groups.md)
**Set a url variable**
**Operation ID:** `putApiV4GroupsIdHooksHookIdUrlVariablesKey`

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

