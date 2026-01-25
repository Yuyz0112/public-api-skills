# GET /accounts/{account_id}/cloudforce-one/events/categories/catalog

**Resource:** [Category](../resources/Category.md)
**Lists categories**
**Operation ID:** `get_CategoryListComplete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of categories. |
| 400 | Bad Request. |

## Security

- **api_token**
