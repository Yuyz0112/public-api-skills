# GET /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/settings

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Get Script Settings**
**Operation ID:** `namespace-worker-get-script-settings`

Get script settings from a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch script settings. |
| 4XX | Fetch script settings failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
