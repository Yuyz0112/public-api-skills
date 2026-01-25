# PATCH /zones/{zone_id}/settings/aegis

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Change aegis setting**
**Operation ID:** `zone-cache-settings-change-aegis-setting`

Aegis provides dedicated egress IPs (from Cloudflare to your origin) for your layer 7 WAF and CDN services. The egress IPs are reserved exclusively for your account so that you can increase your origin security by only allowing traffic from a small list of IP addresses.

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
| 200 | Change aegis setting response. |
| 4XX | Change aegis setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
