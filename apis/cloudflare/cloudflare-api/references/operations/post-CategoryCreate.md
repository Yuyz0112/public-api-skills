# POST /accounts/{account_id}/cloudforce-one/events/categories/create

**Resource:** [Category](../resources/Category.md)
**Creates a new category**
**Operation ID:** `post_CategoryCreate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created category. |
| 400 | Bad Request. |

## Security

- **api_token**
