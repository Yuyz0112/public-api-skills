# DELETE /zones/{zone_id}/rate_limits/{rate_limit_id}

**Resource:** [Rate limits for a zone](../resources/Rate-limits-for-a-zone.md)
**Delete a rate limit**
**Operation ID:** `rate-limits-for-a-zone-delete-a-rate-limit`
⚠️ **Deprecated**

Deletes an existing rate limit.

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
| 200 | Delete a rate limit response. |
| 4XX | Delete a rate limit response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
