# DELETE /accounts/{account_id}/workers/scripts/{script_name}/secrets/{secret_name}

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Delete script secret**
**Operation ID:** `worker-delete-script-secret`

Remove a secret from a script.

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
| 200 | Delete script secret binding. |
| 4XX | Delete script secret failure. |

**Success Response Schema:**

[workers_api-response-null-result](../schemas/workers/workers-api-response-null-result.md)

## Security

- **api_token**
- **api_email**
- **api_key**
