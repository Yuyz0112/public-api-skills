# GET /zones/{zone_id}/rate_limits

**Resource:** [Rate limits for a zone](../resources/Rate-limits-for-a-zone.md)
**List rate limits**
**Operation ID:** `rate-limits-for-a-zone-list-rate-limits`
⚠️ **Deprecated**

Fetches the rate limits for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List rate limits response. |
| 4XX | List rate limits response failure. |

**Success Response Schema:**

[firewall_ratelimit_response_collection](../schemas/firewall/firewall-ratelimit-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
