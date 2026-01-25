# GET /zones/{zone_id}/settings/fonts

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Get Cloudflare Fonts setting**
**Operation ID:** `zone-settings-get-fonts-setting`

Enhance your website's font delivery with Cloudflare Fonts. Deliver Google Hosted fonts from your own domain,
boost performance, and enhance user privacy. Refer to the Cloudflare Fonts documentation for more information.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | speed_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Cloudflare Fonts setting response. |
| 4XX | Get Cloudflare Fonts setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
