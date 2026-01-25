# PUT /accounts/{account_id}/workers/scripts/{script_name}

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Upload Worker Module**
**Operation ID:** `worker-script-upload-worker-module`

Upload a worker module. You can find more about the multipart metadata on our docs: https://developers.cloudflare.com/workers/configuration/multipart-upload-metadata/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload Worker Module response. |
| 4XX | Upload Worker Module response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
