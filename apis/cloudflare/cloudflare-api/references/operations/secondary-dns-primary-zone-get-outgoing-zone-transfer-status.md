# GET /zones/{zone_id}/secondary_dns/outgoing/status

**Resource:** [Secondary DNS (Primary Zone)](../resources/Secondary-DNS-Primary-Zone.md)
**Get Outgoing Zone Transfer Status**
**Operation ID:** `secondary-dns-(-primary-zone)-get-outgoing-zone-transfer-status`

Get primary zone transfer status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | secondary-dns_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Outgoing Zone Transfer Status response. |
| 4XX | Get Outgoing Zone Transfer Status response failure. |

**Success Response Schema:**

[secondary-dns_enable_transfer_response](../schemas/secondary-dns/secondary-dns-enable-transfer-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
