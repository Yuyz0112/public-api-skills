# POST /accounts/{account_id}/workers/scripts/{script_name}/versions

**Resource:** [Worker Versions](../resources/Worker-Versions.md)
**Upload Version**
**Operation ID:** `worker-versions-upload-version`

Upload a Worker Version without deploying to Cloudflare's network. You can find more about the multipart metadata on our docs: https://developers.cloudflare.com/workers/configuration/multipart-upload-metadata/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_schemas-script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload Version response. |
| 4XX | Upload Version response failure. |

**Success Response Schema:**

[workers_versions-upload-response](../schemas/workers/workers-versions-upload-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
