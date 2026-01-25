# DELETE /accounts/{account_id}/workers/scripts/{script_name}/subdomain

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Delete Worker subdomain**
**Operation ID:** `worker-script-delete-subdomain`

Disable all workers.dev subdomains for a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete subdomain response. |
| 4XX | Delete subdomain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
