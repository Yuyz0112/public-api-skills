# GET /accounts/{account_id}/workflows

**Resource:** [Workflows](../resources/Workflows.md)
**List all Workflows**
**Operation ID:** `wor-list-workflows`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per_page` | query | number | No |  |
| `page` | query | number | No |  |
| `search` | query | string | No | Allows filtering workflows` name. |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of all Workflows belonging to a account. |
| 400 | Input Validation Error. |

## Security

- **api_email**
- **api_key**
- **api_token**
