# DELETE /zones/{zone_id}/secondary_dns/outgoing

**Resource:** [Secondary DNS (Primary Zone)](../resources/Secondary-DNS-Primary-Zone.md)
**Delete Primary Zone Configuration**
**Operation ID:** `secondary-dns-(-primary-zone)-delete-primary-zone-configuration`

Delete primary zone configuration for outgoing zone transfers.

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
| 200 | Delete Primary Zone Configuration response. |
| 4XX | Delete Primary Zone Configuration response failure. |

**Success Response Schema:**

[secondary-dns_id_response](../schemas/secondary-dns/secondary-dns-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
