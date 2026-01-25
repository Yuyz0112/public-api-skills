# PATCH /zones/{zone_id}/settings/fonts

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Change Cloudflare Fonts setting**
**Operation ID:** `zone-settings-change-fonts-setting`

Enhance your website's font delivery with Cloudflare Fonts. Deliver Google Hosted fonts from your own domain,
boost performance, and enhance user privacy. Refer to the Cloudflare Fonts documentation for more information.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | speed_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Change Cloudflare Fonts setting response. |
| 4XX | Change Cloudflare Fonts setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
