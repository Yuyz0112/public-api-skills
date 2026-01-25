# GET /zones

**Resource:** [Zone](../resources/Zone.md)
**List Zones**
**Operation ID:** `zones-get`

Lists, searches, sorts, and filters your zones. Listing zones across more than 500 accounts
is currently not allowed.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No |  |
| `status` | query | enum: initializing, pending, active... | No |  |
| `account.id` | query | string | No |  |
| `account.name` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: name, status, account.id... | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `match` | query | enum: any, all | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Zones response. |
| 4XX | List Zones response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
