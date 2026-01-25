# GET /zones/{zone_id}/secondary_dns/incoming

**Resource:** [Secondary DNS (Secondary Zone)](../resources/Secondary-DNS-Secondary-Zone.md)
**Secondary Zone Configuration Details**
**Operation ID:** `secondary-dns-(-secondary-zone)-secondary-zone-configuration-details`

Get secondary zone configuration for incoming zone transfers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | secondary-dns_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Secondary Zone Configuration Details response. |
| 4XX | Secondary Zone Configuration Details response failure. |

**Success Response Schema:**

[secondary-dns_single_response_incoming](../schemas/secondary-dns/secondary-dns-single-response-incoming.md)

## Security

- **api_token**
- **api_email**
- **api_key**
