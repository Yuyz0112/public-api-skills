# POST /zones/{zone_id}/secondary_dns/outgoing

**Resource:** [Secondary DNS (Primary Zone)](../resources/Secondary-DNS-Primary-Zone.md)
**Create Primary Zone Configuration**
**Operation ID:** `secondary-dns-(-primary-zone)-create-primary-zone-configuration`

Create primary zone configuration for outgoing zone transfers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | secondary-dns_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [secondary-dns_single_request_outgoing](../schemas/secondary-dns/secondary-dns-single-request-outgoing.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Primary Zone Configuration response. |
| 4XX | Create Primary Zone Configuration response failure. |

**Success Response Schema:**

[secondary-dns_single_response_outgoing](../schemas/secondary-dns/secondary-dns-single-response-outgoing.md)

## Security

- **api_token**
- **api_email**
- **api_key**
