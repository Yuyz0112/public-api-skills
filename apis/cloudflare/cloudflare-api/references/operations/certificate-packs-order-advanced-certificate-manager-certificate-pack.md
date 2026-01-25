# POST /zones/{zone_id}/ssl/certificate_packs/order

**Resource:** [Certificate Packs](../resources/Certificate-Packs.md)
**Order Advanced Certificate Manager Certificate Pack**
**Operation ID:** `certificate-packs-order-advanced-certificate-manager-certificate-pack`

For a given zone, order an advanced certificate pack.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Order Advanced Certificate Manager Certificate Pack response |
| 4XX | Order Advanced Certificate Manager Certificate Pack response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_advanced_certificate_pack_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-advanced-certificate-pack-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
