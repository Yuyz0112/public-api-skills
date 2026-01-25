# GET /zones/{zone_id}/cache/tiered_cache_smart_topology_enable

**Resource:** [Smart Tiered Cache](../resources/Smart-Tiered-Cache.md)
**Get Smart Tiered Cache setting**
**Operation ID:** `smart-tiered-cache-get-smart-tiered-cache-setting`

Smart Tiered Cache dynamically selects the single closest upper tier for each of your website’s origins with no configuration required, using our in-house performance and routing data. Cloudflare collects latency data for each request to an origin, and uses the latency data to determine how well any upper-tier data center is connected with an origin. As a result, Cloudflare can select the data center with the lowest latency to be the upper-tier for an origin.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Smart Tiered Cache setting response. |
| 4XX | Get Smart Tiered Cache setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
