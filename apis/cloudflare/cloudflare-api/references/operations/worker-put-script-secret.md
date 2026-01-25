# PUT /accounts/{account_id}/workers/scripts/{script_name}/secrets

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Add script secret**
**Operation ID:** `worker-put-script-secret`

Add a secret to a script.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_secret](../schemas/workers/workers-secret.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Put script secret binding success. |
| 4XX | Put script secret binding failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
