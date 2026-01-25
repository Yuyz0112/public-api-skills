# GET /zones/{zone_id}/custom_certificates

**Resource:** [Custom SSL for a Zone](../resources/Custom-SSL-for-a-Zone.md)
**List SSL Configurations**
**Operation ID:** `custom-ssl-for-a-zone-list-ssl-configurations`

List, search, and filter all of your custom SSL certificates. The higher priority will break ties across overlapping 'legacy_custom' certificates, but 'legacy_custom' certificates will always supercede 'sni_custom' certificates.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `match` | query | enum: any, all | No |  |
| `status` | query | enum: active, expired, deleted... | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List SSL Configurations response |
| 4XX | List SSL Configurations response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
