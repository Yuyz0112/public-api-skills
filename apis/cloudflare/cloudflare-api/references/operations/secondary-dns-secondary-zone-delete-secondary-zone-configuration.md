# DELETE /zones/{zone_id}/secondary_dns/incoming

**Resource:** [Secondary DNS (Secondary Zone)](../resources/Secondary-DNS-Secondary-Zone.md)
**Delete Secondary Zone Configuration**
**Operation ID:** `secondary-dns-(-secondary-zone)-delete-secondary-zone-configuration`

Delete secondary zone configuration for incoming zone transfers.

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
| 200 | Delete Secondary Zone Configuration response. |
| 4XX | Delete Secondary Zone Configuration response failure. |

**Success Response Schema:**

[secondary-dns_id_response](../schemas/secondary-dns/secondary-dns-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
