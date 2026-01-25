# GET /accounts/{account_id}/storage/kv/namespaces

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**List Namespaces**
**Operation ID:** `workers-kv-namespace-list-namespaces`

Returns the namespaces owned by an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers-kv_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: id, title | No |  |
| `direction` | query | enum: asc, desc | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Namespaces response. |
| 4XX | List Namespaces response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
