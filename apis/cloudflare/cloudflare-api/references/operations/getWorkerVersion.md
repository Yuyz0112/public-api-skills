# GET /accounts/{account_id}/workers/workers/{worker_id}/versions/{version_id}

**Resource:** [Versions](../resources/Versions.md)
**Get Version**
**Operation ID:** `getWorkerVersion`

Get details about a specific version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |
| `version_id` | path | string | Yes |  |
| `include` | query | enum: modules | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get version success. |
| 4XX | Get version failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
