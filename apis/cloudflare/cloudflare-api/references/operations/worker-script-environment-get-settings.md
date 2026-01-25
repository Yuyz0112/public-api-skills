# GET /accounts/{account_id}/workers/services/{service_name}/environments/{environment_name}/settings

**Resource:** [Worker Environment](../resources/Worker-Environment.md)
**Get Script Settings**
**Operation ID:** `worker-script-environment-get-settings`

Get script settings from a worker with an environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `service_name` | path | workers_service | Yes |  |
| `environment_name` | path | workers_environment | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch script settings. |
| 4XX | Fetch script settings failure. |

**Success Response Schema:**

[workers_script-settings-response](../schemas/workers/workers-script-settings-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
