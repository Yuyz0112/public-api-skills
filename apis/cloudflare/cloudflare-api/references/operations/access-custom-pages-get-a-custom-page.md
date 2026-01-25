# GET /accounts/{account_id}/access/custom_pages/{custom_page_id}

**Resource:** [Access custom pages](../resources/Access-custom-pages.md)
**Get a custom page**
**Operation ID:** `access-custom-pages-get-a-custom-page`

Fetches a custom page and also returns its HTML.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_page_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a custom page response |
| 4XX | Get a custom page response failure |

**Success Response Schema:**

[access_custom-pages_components-schemas-single_response](../schemas/access/access-custom-pages-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
