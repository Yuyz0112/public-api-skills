# GET /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**List all TCP Flow Protection filters.**
**Operation ID:** `listTcpFlowProtectionFiltersForAccount`

List all TCP Flow Protection filters for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `mode` | query | string | No | The mode of the filters to get. Optional. Valid values: 'enabled', 'disabled', 'monitoring'. |
| `page` | query | integer (int64) | No | The page number for pagination. Defaults to 1. |
| `per_page` | query | integer (int64) | No | The number of items per page. Must be between 10 and 1000. Defaults to 25. |
| `order` | query | string | No | The field to order by. Defaults to 'prefix'. |
| `direction` | query | string | No | The direction of ordering (ASC or DESC). Defaults to 'ASC'. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List all TCP Flow Protection filters response. |
| 4XX | List all TCP Flow Protection filters failure. |

**Success Response Schema:**

[dos_expression-filter-list-response](../schemas/dos/dos-expression-filter-list-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
