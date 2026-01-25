# POST /zones/{zone_id}/secondary_dns/outgoing/enable

**Resource:** [Secondary DNS (Primary Zone)](../resources/Secondary-DNS-Primary-Zone.md)
**Enable Outgoing Zone Transfers**
**Operation ID:** `secondary-dns-(-primary-zone)-enable-outgoing-zone-transfers`

Enable outgoing zone transfers for primary zone.

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
| 200 | Enable Outgoing Zone Transfers response. |
| 4XX | Enable Outgoing Zone Transfers response failure. |

**Success Response Schema:**

[secondary-dns_enable_transfer_response](../schemas/secondary-dns/secondary-dns-enable-transfer-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
