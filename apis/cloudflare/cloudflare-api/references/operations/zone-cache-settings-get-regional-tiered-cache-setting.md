# GET /zones/{zone_id}/cache/regional_tiered_cache

**Resource:** [Zone Cache Settings](../resources/Zone-Cache-Settings.md)
**Get Regional Tiered Cache setting**
**Operation ID:** `zone-cache-settings-get-regional-tiered-cache-setting`

Instructs Cloudflare to check a regional hub data center on the way to your upper tier. This can help improve performance for smart and custom tiered cache topologies.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Regional Tiered Cache setting response. |
| 4XX | Get Regional Tiered Cache setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
