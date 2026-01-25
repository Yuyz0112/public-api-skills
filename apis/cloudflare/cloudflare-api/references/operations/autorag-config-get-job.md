# GET /accounts/{account_id}/autorag/rags/{id}/jobs/{job_id}

**Resource:** [AutoRAG Jobs](../resources/AutoRAG-Jobs.md)
**Get a Job Details**
**Operation ID:** `autorag-config-get-job`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | rag id |
| `job_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a AutoRAG Job Details |
| 404 | job_not_found |
| 503 | unable_to_connect_to_autorag |

## Security

- **api_token**
- **api_email**
- **api_key**
