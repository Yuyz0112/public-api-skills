# POST /zones/{zone_id}/rate_limits

**Resource:** [Rate limits for a zone](../resources/Rate-limits-for-a-zone.md)
**Create a rate limit**
**Operation ID:** `rate-limits-for-a-zone-create-a-rate-limit`
⚠️ **Deprecated**

Creates a new rate limit for a zone. Refer to the object definition for a list of required attributes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a rate limit response. |
| 4XX | Create a rate limit response failure. |

**Success Response Schema:**

[firewall_ratelimit_response_single](../schemas/firewall/firewall-ratelimit-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
