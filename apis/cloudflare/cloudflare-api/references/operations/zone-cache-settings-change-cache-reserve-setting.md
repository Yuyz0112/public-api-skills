# PATCH /zones/{zone_id}/cache/cache_reserve

**Resource:** [Zone Cache Settings](../resources/Zone-Cache-Settings.md)
**Change Cache Reserve setting**
**Operation ID:** `zone-cache-settings-change-cache-reserve-setting`

Increase cache lifetimes by automatically storing all cacheable files into Cloudflare's persistent object storage buckets. Requires Cache Reserve subscription. Note: using Tiered Cache with Cache Reserve is highly recommended to reduce Reserve operations costs. See the [developer docs](https://developers.cloudflare.com/cache/about/cache-reserve) for more information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Change Cache Reserve setting response. |
| 4XX | Change Cache Reserve setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
