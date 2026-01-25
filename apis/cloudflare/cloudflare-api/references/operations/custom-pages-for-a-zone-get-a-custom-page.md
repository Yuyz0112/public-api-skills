# GET /zones/{zone_identifier}/custom_pages/{identifier}

**Resource:** [Custom pages for a zone](../resources/Custom-pages-for-a-zone.md)
**Get a custom page**
**Operation ID:** `custom-pages-for-a-zone-get-a-custom-page`

Fetches the details of a custom page.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | custom-pages_error_page_type | Yes |  |
| `zone_identifier` | path | custom-pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a custom page response |
| 4xx | Get a custom page response failure |

**Success Response Schema:**

[custom-pages_custom_page](../schemas/custom-pages/custom-pages-custom-page.md)

## Security

- **api_email**
- **api_key**
