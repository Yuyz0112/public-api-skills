# GET /zones/{zone_id}/settings/speed_brain

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Get Cloudflare Speed Brain setting**
**Operation ID:** `zone-settings-get-speed-brain-setting`

Speed Brain lets compatible browsers speculate on content which can be prefetched or preloaded, making website
navigation faster. Refer to the Cloudflare Speed Brain documentation for more information.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | speed_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Cloudflare Speed Brain setting response. |
| 4XX | Get Cloudflare Speed Brain setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
