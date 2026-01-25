# GET /accounts/{account_id}/ai-search/instances/{id}/jobs/{job_id}

**Resource:** [AI Search Instances Jobs](../resources/AI-Search-Instances-Jobs.md)
**Get a Job Details**
**Operation ID:** `ai-search-instance-get-job`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Use your AI Search ID. |
| `job_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a AI Search Job Details. |
| 400 | Bad Request. |
| 500 | Internal Error. |

## Security

- **api_token**
- **api_email**
- **api_key**
