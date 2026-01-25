# GET /accounts/{account_id}/cloudforce-one/events/tags/categories

**Resource:** [TagCategory](../resources/TagCategory.md)
**Lists all tag categories (SoT)**
**Operation ID:** `get_TagCategoryList`

Returns all Source-of-Truth tag categories for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of tag categories. |
| 400 | Bad Request. |

## Security

- **api_token**
