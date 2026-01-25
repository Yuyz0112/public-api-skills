# DELETE /zones/{zone_id}/ssl/certificate_packs/{certificate_pack_id}

**Resource:** [Certificate Packs](../resources/Certificate-Packs.md)
**Delete Advanced Certificate Manager Certificate Pack**
**Operation ID:** `certificate-packs-delete-advanced-certificate-manager-certificate-pack`

For a given zone, delete an advanced certificate pack.

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
| 200 | Delete Advanced Certificate Manager Certificate Pack response |
| 4XX | Delete Advanced Certificate Manager Certificate Pack response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_delete_advanced_certificate_pack_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-delete-advanced-certificate-pack-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
