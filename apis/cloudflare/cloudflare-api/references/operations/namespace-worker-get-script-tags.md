# GET /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/tags

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Get Script Tags**
**Operation ID:** `namespace-worker-get-script-tags`

Fetch tags from a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch script tags. |
| 4XX | Fetch script tags failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
