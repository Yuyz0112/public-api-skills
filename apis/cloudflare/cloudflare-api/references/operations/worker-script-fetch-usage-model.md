# GET /accounts/{account_id}/workers/scripts/{script_name}/usage-model

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Fetch Usage Model**
**Operation ID:** `worker-script-fetch-usage-model`

Fetches the Usage Model for a given Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch Usage Model response. |
| 4XX | Fetch Usage Model response failure. |

**Success Response Schema:**

[workers_usage-model-response](../schemas/workers/workers-usage-model-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
