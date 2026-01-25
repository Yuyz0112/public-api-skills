# PATCH /zones/{zone_id}/ssl/certificate_packs/{certificate_pack_id}

**Resource:** [Certificate Packs](../resources/Certificate-Packs.md)
**Restart Validation or Update Advanced Certificate Manager Certificate Pack**
**Operation ID:** `certificate-packs-restart-validation-for-advanced-certificate-manager-certificate-pack`

For a given zone, restart validation or add cloudflare branding for an advanced certificate pack.  The former is only a validation operation for a Certificate Pack in a validation_timed_out status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_pack_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Restart Validation for Advanced Certificate Manager Certificate Pack response |
| 4XX | Restart Validation for Advanced Certificate Manager Certificate Pack response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_advanced_certificate_pack_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-advanced-certificate-pack-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
