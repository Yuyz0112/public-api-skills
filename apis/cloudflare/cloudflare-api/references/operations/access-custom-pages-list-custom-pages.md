# GET /accounts/{account_id}/access/custom_pages

**Resource:** [Access custom pages](../resources/Access-custom-pages.md)
**List custom pages**
**Operation ID:** `access-custom-pages-list-custom-pages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List custom pages response |
| 4XX | List custom pages response failure |

**Success Response Schema:**

[access_custom-pages_components-schemas-response_collection](../schemas/access/access-custom-pages-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
