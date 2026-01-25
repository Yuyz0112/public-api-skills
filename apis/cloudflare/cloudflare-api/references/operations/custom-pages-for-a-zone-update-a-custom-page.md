# PUT /zones/{zone_identifier}/custom_pages/{identifier}

**Resource:** [Custom pages for a zone](../resources/Custom-pages-for-a-zone.md)
**Update a custom page**
**Operation ID:** `custom-pages-for-a-zone-update-a-custom-page`

Updates the configuration of an existing custom page.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | custom-pages_error_page_type | Yes |  |
| `zone_identifier` | path | custom-pages_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a custom page response |
| 4xx | Update a custom page response failure |

**Success Response Schema:**

[custom-pages_custom_page_result](../schemas/custom-pages/custom-pages-custom-page-result.md)

## Security

- **api_email**
- **api_key**
