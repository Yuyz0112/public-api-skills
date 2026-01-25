# PATCH /accounts/{account_id}/workers/scripts/{script_name}/settings

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Patch Settings**
**Operation ID:** `worker-script-patch-settings`

Patch metadata or config, such as bindings or usage model.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch settings. |
| 4XX | Patch settings failure. |

**Success Response Schema:**

[workers_script-and-version-settings-response](../schemas/workers/workers-script-and-version-settings-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
