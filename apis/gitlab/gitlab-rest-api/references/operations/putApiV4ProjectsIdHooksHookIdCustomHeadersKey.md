# PUT /api/v4/projects/{id}/hooks/{hook_id}/custom_headers/{key}

**Resource:** [projects](../resources/projects.md)
**Set a custom header**
**Operation ID:** `putApiV4ProjectsIdHooksHookIdCustomHeadersKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the hook |
| `key` | path | string | Yes | The key of the custom header |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

