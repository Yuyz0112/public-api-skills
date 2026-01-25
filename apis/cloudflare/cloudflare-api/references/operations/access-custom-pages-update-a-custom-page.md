# PUT /accounts/{account_id}/access/custom_pages/{custom_page_id}

**Resource:** [Access custom pages](../resources/Access-custom-pages.md)
**Update a custom page**
**Operation ID:** `access-custom-pages-update-a-custom-page`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_page_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [access_custom_page](../schemas/access/access-custom-page.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a custom page response |
| 4XX | Update a custom page response failure |

**Success Response Schema:**

[access_single_response_without_html](../schemas/access/access-single-response-without-html.md)

## Security

- **api_email**
- **api_key**
- **api_token**
