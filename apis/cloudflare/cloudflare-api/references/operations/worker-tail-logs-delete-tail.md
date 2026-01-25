# DELETE /accounts/{account_id}/workers/scripts/{script_name}/tails/{id}

**Resource:** [Worker Tail Logs](../resources/Worker-Tail-Logs.md)
**Delete Tail**
**Operation ID:** `worker-tail-logs-delete-tail`

Deletes a tail from a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `id` | path | workers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Tail response. |
| 4XX | Delete Tail response failure. |

**Success Response Schema:**

[workers_api-response-common](../schemas/workers/workers-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
