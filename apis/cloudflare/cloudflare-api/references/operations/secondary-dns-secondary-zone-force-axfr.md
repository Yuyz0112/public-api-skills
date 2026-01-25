# POST /zones/{zone_id}/secondary_dns/force_axfr

**Resource:** [Secondary DNS (Secondary Zone)](../resources/Secondary-DNS-Secondary-Zone.md)
**Force AXFR**
**Operation ID:** `secondary-dns-(-secondary-zone)-force-axfr`

Sends AXFR zone transfer request to primary nameserver(s).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | secondary-dns_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Force AXFR response. |
| 4XX | Force AXFR response failure. |

**Success Response Schema:**

[secondary-dns_force_response](../schemas/secondary-dns/secondary-dns-force-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
