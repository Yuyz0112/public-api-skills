# POST /accounts/{account_id}/access/custom_pages

**Resource:** [Access custom pages](../resources/Access-custom-pages.md)
**Create a custom page**
**Operation ID:** `access-custom-pages-create-a-custom-page`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [access_custom_page](../schemas/access/access-custom-page.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create a custom page response |
| 4XX | Create a custom page response failure |

**Success Response Schema:**

[access_single_response_without_html](../schemas/access/access-single-response-without-html.md)

## Security

- **api_email**
- **api_key**
- **api_token**
