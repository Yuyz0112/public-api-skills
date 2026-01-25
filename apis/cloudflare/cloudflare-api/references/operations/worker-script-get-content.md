# GET /accounts/{account_id}/workers/scripts/{script_name}/content/v2

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Get script content**
**Operation ID:** `worker-script-get-content`

Fetch script content only.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch script content. |
| 4XX | Fetch script content failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
