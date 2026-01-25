# PUT /zones/{zone_id}/rate_limits/{rate_limit_id}

**Resource:** [Rate limits for a zone](../resources/Rate-limits-for-a-zone.md)
**Update a rate limit**
**Operation ID:** `rate-limits-for-a-zone-update-a-rate-limit`
⚠️ **Deprecated**

Updates an existing rate limit.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rate_limit_id` | path | firewall_rate_limit_id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a rate limit response. |
| 4XX | Update a rate limit response failure. |

**Success Response Schema:**

[firewall_ratelimit_response_single](../schemas/firewall/firewall-ratelimit-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
