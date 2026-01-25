# GET /accounts/{account_id}/workers/scripts/{script_name}

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Download Worker**
**Operation ID:** `worker-script-download-worker`

Fetch raw script content for your worker. Note this is the original script content, not JSON encoded.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Worker successfully downloaded. Returns script content as a multipart form, with no metadata part and no JSON encoding applied. |
| 4XX | Download Worker response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
