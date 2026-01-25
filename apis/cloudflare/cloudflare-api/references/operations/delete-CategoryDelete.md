# DELETE /accounts/{account_id}/cloudforce-one/events/categories/{category_id}

**Resource:** [Category](../resources/Category.md)
**Deletes a category**
**Operation ID:** `delete_CategoryDelete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `category_id` | path | string (uuid) | Yes | Category UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the uuid of the deleted category. |
| 400 | Bad Request. |

## Security

- **api_token**
