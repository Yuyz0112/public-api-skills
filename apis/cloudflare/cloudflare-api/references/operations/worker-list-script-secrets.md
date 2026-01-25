# GET /accounts/{account_id}/workers/scripts/{script_name}/secrets

**Resource:** [Worker Script](../resources/Worker-Script.md)
**List script secrets**
**Operation ID:** `worker-list-script-secrets`

List secrets bound to a script.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
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
