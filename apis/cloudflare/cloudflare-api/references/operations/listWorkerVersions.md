# GET /accounts/{account_id}/workers/workers/{worker_id}/versions

**Resource:** [Versions](../resources/Versions.md)
**List Versions**
**Operation ID:** `listWorkerVersions`

List all versions for a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |
| `page` | query | integer | No | Current page. |
| `per_page` | query | integer | No | Items per-page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List versions success. |
| 4XX | List versions failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
