# GET /accounts/{account_id}/workers/scripts/{script_name}/secrets/{secret_name}

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Get secret binding**
**Operation ID:** `worker-get-script-secret`

Get a given secret binding (value omitted) on a script.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `secret_name` | path | workers_secret_name | Yes |  |
| `url_encoded` | query | workers_secret_name_url_encoded | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get script secret binding. |
| 4XX | Get script secret failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
