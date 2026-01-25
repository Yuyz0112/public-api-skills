# POST /zones/{zone_id}/secondary_dns/incoming

**Resource:** [Secondary DNS (Secondary Zone)](../resources/Secondary-DNS-Secondary-Zone.md)
**Create Secondary Zone Configuration**
**Operation ID:** `secondary-dns-(-secondary-zone)-create-secondary-zone-configuration`

Create secondary zone configuration for incoming zone transfers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | secondary-dns_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [secondary-dns_dns-secondary-secondary-zone](../schemas/secondary-dns/secondary-dns-dns-secondary-secondary-zone.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Secondary Zone Configuration response. |
| 4XX | Create Secondary Zone Configuration response failure. |

**Success Response Schema:**

[secondary-dns_single_response_incoming](../schemas/secondary-dns/secondary-dns-single-response-incoming.md)

## Security

- **api_token**
- **api_email**
- **api_key**
