# PATCH /accounts/{account_id}/workers/scripts/{script_name}/script-settings

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Patch Script Settings**
**Operation ID:** `worker-script-settings-patch-settings`

Patch script-level settings when using [Worker Versions](https://developers.cloudflare.com/api/operations/worker-versions-list-versions). Including but not limited to Logpush and Tail Consumers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_script-settings-item](../schemas/workers/workers-script-settings-item.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch script settings. |
| 4XX | Patch script settings failure. |

**Success Response Schema:**

[workers_script-settings-response](../schemas/workers/workers-script-settings-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
