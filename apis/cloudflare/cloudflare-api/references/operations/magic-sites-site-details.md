# GET /accounts/{account_id}/magic/sites/{site_id}

**Resource:** [Magic Sites](../resources/Magic-Sites.md)
**Site Details**
**Operation ID:** `magic-sites-site-details`

Get a specific Site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Site Details response |
| 4XX | Site Details response failure |

**Success Response Schema:**

[magic_site_single_response](../schemas/magic/magic-site-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
