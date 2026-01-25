# GET /accounts/{account_id}/workers/services/{service_name}/environments/{environment_name}/content

**Resource:** [Worker Environment](../resources/Worker-Environment.md)
**Get script content**
**Operation ID:** `worker-environment-get-script-content`

Get script content from a worker with an environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `service_name` | path | workers_service | Yes |  |
| `environment_name` | path | workers_environment | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get script content. |
| 4XX | Get script content failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
