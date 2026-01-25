# GET /zones/{zone_id}/settings/origin_max_http_version

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Get Origin Max HTTP Version Setting**
**Operation ID:** `zone-cache-settings-get-origin-max-http-version-setting`

Origin Max HTTP Setting Version sets the highest HTTP version Cloudflare will attempt to use with your origin. This setting allows Cloudflare to make HTTP/2 requests to your origin. (Refer to [Enable HTTP/2 to Origin](https://developers.cloudflare.com/cache/how-to/enable-http2-to-origin/), for more information.). The default value is "2" for all plan types except Enterprise where it is "1".

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Origin Max HTTP Version setting response. |
| 4XX | Get Origin Max HTTP Version setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
