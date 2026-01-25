# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/datasets

**Resource:** [AI Gateway Datasets](../resources/AI-Gateway-Datasets.md)
**List Datasets**
**Operation ID:** `aig-config-list-dataset`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `name` | query | string | No |  |
| `enable` | query | boolean | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List objects |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
