# GET /accounts/{account_id}/cloudforce-one/events/categories/{category_id}

**Resource:** [Category](../resources/Category.md)
**Reads a category**
**Operation ID:** `get_CategoryRead`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `category_id` | path | string (uuid) | Yes | Category UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a category. |
| 400 | Bad Request. |

## Security

- **api_token**
