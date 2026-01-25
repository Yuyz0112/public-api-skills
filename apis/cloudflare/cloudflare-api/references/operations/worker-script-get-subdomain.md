# GET /accounts/{account_id}/workers/scripts/{script_name}/subdomain

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Get Worker subdomain**
**Operation ID:** `worker-script-get-subdomain`

Get if the Worker is available on the workers.dev subdomain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get subdomain response. |
| 4XX | Get subdomain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
