# PATCH /accounts/{account_id}/cloudforce-one/events/tags/categories/{category_uuid}

**Resource:** [TagCategory](../resources/TagCategory.md)
**Updates a tag category (SoT)**
**Operation ID:** `patch_TagCategoryUpdate`

Updates a Source-of-Truth tag category by UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `category_uuid` | path | string | Yes | Tag Category UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated tag category. |
| 400 | Bad Request. |
| 404 | Bad Request. |
| 409 | Bad Request. |

## Security

- **api_token**
