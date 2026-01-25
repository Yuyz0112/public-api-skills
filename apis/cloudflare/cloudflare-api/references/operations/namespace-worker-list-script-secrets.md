# GET /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/secrets

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**List Script Secrets**
**Operation ID:** `namespace-worker-list-script-secrets`

List secrets bound to a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List script secrets. |
| 4XX | List script secrets failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
