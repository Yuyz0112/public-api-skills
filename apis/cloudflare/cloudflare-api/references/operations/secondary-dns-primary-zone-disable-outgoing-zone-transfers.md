# POST /zones/{zone_id}/secondary_dns/outgoing/disable

**Resource:** [Secondary DNS (Primary Zone)](../resources/Secondary-DNS-Primary-Zone.md)
**Disable Outgoing Zone Transfers**
**Operation ID:** `secondary-dns-(-primary-zone)-disable-outgoing-zone-transfers`

Disable outgoing zone transfers for primary zone and clears IXFR backlog of primary zone.

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
| 200 | Disable Outgoing Zone Transfers response. |
| 4XX | Disable Outgoing Zone Transfers response failure. |

**Success Response Schema:**

[secondary-dns_disable_transfer_response](../schemas/secondary-dns/secondary-dns-disable-transfer-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
