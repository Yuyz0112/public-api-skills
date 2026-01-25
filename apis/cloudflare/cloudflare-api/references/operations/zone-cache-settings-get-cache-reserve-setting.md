# GET /zones/{zone_id}/cache/cache_reserve

**Resource:** [Zone Cache Settings](../resources/Zone-Cache-Settings.md)
**Get Cache Reserve setting**
**Operation ID:** `zone-cache-settings-get-cache-reserve-setting`

Increase cache lifetimes by automatically storing all cacheable files into Cloudflare's persistent object storage buckets. Requires Cache Reserve subscription. Note: using Tiered Cache with Cache Reserve is highly recommended to reduce Reserve operations costs. See the [developer docs](https://developers.cloudflare.com/cache/about/cache-reserve) for more information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Cache Reserve setting response. |
| 4XX | Get Cache Reserve setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
