# GET /zones/{zone_id}/ssl/certificate_packs/{certificate_pack_id}

**Resource:** [Certificate Packs](../resources/Certificate-Packs.md)
**Get Certificate Pack**
**Operation ID:** `certificate-packs-get-certificate-pack`

For a given zone, get a certificate pack.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_pack_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Certificate Pack response |
| 4XX | Get Certificate Pack response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_pack_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-pack-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
