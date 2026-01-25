# POST /accounts/{account_id}/cloudforce-one/events/tags/categories/create

**Resource:** [TagCategory](../resources/TagCategory.md)
**Creates a new tag category (SoT)**
**Operation ID:** `post_TagCategoryCreate`

Creates a new Source-of-Truth tag category for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created tag category. |
| 400 | Bad Request. |
| 409 | Bad Request. |

## Security

- **api_token**
