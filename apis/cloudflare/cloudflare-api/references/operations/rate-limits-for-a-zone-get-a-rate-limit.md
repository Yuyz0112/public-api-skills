# GET /zones/{zone_id}/rate_limits/{rate_limit_id}

**Resource:** [Rate limits for a zone](../resources/Rate-limits-for-a-zone.md)
**Get a rate limit**
**Operation ID:** `rate-limits-for-a-zone-get-a-rate-limit`
⚠️ **Deprecated**

Fetches the details of a rate limit.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rate_limit_id` | path | firewall_rate_limit_id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a rate limit response. |
| 4XX | Get a rate limit response failure. |

**Success Response Schema:**

[firewall_ratelimit_response_single](../schemas/firewall/firewall-ratelimit-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
