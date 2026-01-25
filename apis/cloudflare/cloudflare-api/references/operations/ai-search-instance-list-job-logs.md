# GET /accounts/{account_id}/ai-search/instances/{id}/jobs/{job_id}/logs

**Resource:** [AI Search Instances Jobs](../resources/AI-Search-Instances-Jobs.md)
**List Job Logs**
**Operation ID:** `ai-search-instance-list-job-logs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Use your AI Search ID. |
| `job_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of AI Search Job Logs. |
| 400 | Bad Request. |
| 500 | Internal Error. |

## Security

- **api_token**
- **api_email**
- **api_key**
