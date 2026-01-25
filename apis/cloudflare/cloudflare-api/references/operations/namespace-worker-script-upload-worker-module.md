# PUT /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Upload Worker Module**
**Operation ID:** `namespace-worker-script-upload-worker-module`

Upload a worker module to a Workers for Platforms namespace. You can find more about the multipart metadata on our docs: https://developers.cloudflare.com/workers/configuration/multipart-upload-metadata/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
