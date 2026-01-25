# GET /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/secrets/{secret_name}

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Get secret binding**
**Operation ID:** `namespace-worker-get-script-secrets`

Get a given secret binding (value omitted) on a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `secret_name` | path | workers_secret_name | Yes |  |
| `url_encoded` | query | workers_secret_name_url_encoded | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get script secret (Workers for Platforms). |
| 4XX | Get script secret failure (Workers for Platforms). |

## Security

- **api_token**
- **api_email**
- **api_key**
