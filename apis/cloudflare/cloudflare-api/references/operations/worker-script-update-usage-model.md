# PUT /accounts/{account_id}/workers/scripts/{script_name}/usage-model

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Update Usage Model**
**Operation ID:** `worker-script-update-usage-model`

Updates the Usage Model for a given Worker. Requires a Workers Paid subscription.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Usage Model response. |
| 4XX | Update Usage Model response failure. |

**Success Response Schema:**

[workers_usage-model-response](../schemas/workers/workers-usage-model-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
