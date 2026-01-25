# POST /accounts/{account_id}/cloudforce-one/events/categories/{category_id}

**Resource:** [Category](../resources/Category.md)
**Updates a category**
**Operation ID:** `post_CategoryUpdate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `category_id` | path | string (uuid) | Yes | Category UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated category. |
| 400 | Bad Request. |

## Security

- **api_token**
