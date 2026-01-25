# GET /zones/{zone_id}/secondary_dns/outgoing

**Resource:** [Secondary DNS (Primary Zone)](../resources/Secondary-DNS-Primary-Zone.md)
**Primary Zone Configuration Details**
**Operation ID:** `secondary-dns-(-primary-zone)-primary-zone-configuration-details`

Get primary zone configuration for outgoing zone transfers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | secondary-dns_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Primary Zone Configuration Details response. |
| 4XX | Primary Zone Configuration Details response failure. |

**Success Response Schema:**

[secondary-dns_single_response_outgoing](../schemas/secondary-dns/secondary-dns-single-response-outgoing.md)

## Security

- **api_token**
- **api_email**
- **api_key**
