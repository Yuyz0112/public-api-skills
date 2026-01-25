# GET /accounts/{account_id}/load_balancers/search

**Resource:** [Account Load Balancer Search](../resources/Account-Load-Balancer-Search.md)
**Search Resources**
**Operation ID:** `account-load-balancer-search-search-resources`

Search for Load Balancing resources.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |
| `query` | query | string | No |  |
| `references` | query | enum: , *, referral... | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Search Resources response. |
| 4XX | Search Resources response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
