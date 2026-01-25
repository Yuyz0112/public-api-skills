# GET /accounts/{account_id}/workers/scripts/{script_name}/script-settings

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Get Script Settings**
**Operation ID:** `worker-script-settings-get-settings`

Get script-level settings when using [Worker Versions](https://developers.cloudflare.com/api/operations/worker-versions-list-versions). Includes Logpush and Tail Consumers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch script settings. |
| 4XX | Fetch script settings failure. |

**Success Response Schema:**

[workers_script-settings-response](../schemas/workers/workers-script-settings-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
