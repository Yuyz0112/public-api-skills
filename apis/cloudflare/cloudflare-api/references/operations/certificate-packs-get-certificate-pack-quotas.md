# GET /zones/{zone_id}/ssl/certificate_packs/quota

**Resource:** [Certificate Packs](../resources/Certificate-Packs.md)
**Get Certificate Pack Quotas**
**Operation ID:** `certificate-packs-get-certificate-pack-quotas`

For a given zone, list certificate pack quotas.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Certificate Pack Quotas response |
| 4XX | Get Certificate Pack Quotas response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_pack_quota_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-pack-quota-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
