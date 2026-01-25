# POST /accounts/{account_id}/ai-search/instances/{id}/jobs

**Resource:** [AI Search Instances Jobs](../resources/AI-Search-Instances-Jobs.md)
**Create new job**
**Operation ID:** `ai-search-instance-create-job`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Use your AI Search ID. |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the AI Search job id. |
| 400 | Bad Request. |
| 500 | Internal Error. |

## Security

- **api_token**
- **api_email**
- **api_key**
