# GET /accounts/{account_id}/d1/database

**Resource:** [D1](../resources/D1.md)
**List D1 Databases**
**Operation ID:** `cloudflare-d1-list-databases`

Returns a list of D1 databases.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | d1_account-identifier | Yes |  |
| `name` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List D1 databases response |
| 4XX | List D1 databases response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
