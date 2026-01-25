# GET /accounts/{account_id}/autorag/rags/{id}/jobs/{job_id}/logs

**Resource:** [AutoRAG Jobs](../resources/AutoRAG-Jobs.md)
**List Job Logs**
**Operation ID:** `autorag-config-list-job-logs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | rag id |
| `job_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of AutoRAG Job Logs |
| 404 | autorag_not_found |
| 503 | unable_to_connect_to_autorag |

## Security

- **api_token**
- **api_email**
- **api_key**
