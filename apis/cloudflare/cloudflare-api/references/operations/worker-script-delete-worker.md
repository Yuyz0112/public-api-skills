# DELETE /accounts/{account_id}/workers/scripts/{script_name}

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Delete Worker**
**Operation ID:** `worker-script-delete-worker`

Delete your worker. This call has no response body on a successful delete.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `force` | query | boolean | No | If set to true, delete will not be stopped by associated service binding, durable object, or other binding. Any of these associated bindings/durable objects will be deleted along with the script. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Worker response. |
| 4XX | Delete Worker response failure. |

**Success Response Schema:**

[workers_api-response-null-result](../schemas/workers/workers-api-response-null-result.md)

## Security

- **api_token**
- **api_email**
- **api_key**
