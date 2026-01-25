# GET /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/content

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Get Script Content**
**Operation ID:** `namespace-worker-get-script-content`

Fetch script content from a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get script content. |
| 4XX | Get script content failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
