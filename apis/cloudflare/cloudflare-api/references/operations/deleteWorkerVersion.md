# DELETE /accounts/{account_id}/workers/workers/{worker_id}/versions/{version_id}

**Resource:** [Versions](../resources/Versions.md)
**Delete Version**
**Operation ID:** `deleteWorkerVersion`

Delete a version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |
| `version_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete version success. |
| 4XX | Delete version failure. |

**Success Response Schema:**

[workers_api-response-common](../schemas/workers/workers-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
