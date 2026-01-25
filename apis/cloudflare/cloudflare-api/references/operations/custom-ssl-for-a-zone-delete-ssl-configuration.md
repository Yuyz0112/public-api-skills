# DELETE /zones/{zone_id}/custom_certificates/{custom_certificate_id}

**Resource:** [Custom SSL for a Zone](../resources/Custom-SSL-for-a-Zone.md)
**Delete SSL Configuration**
**Operation ID:** `custom-ssl-for-a-zone-delete-ssl-configuration`

Remove a SSL certificate from a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete SSL Configuration response |
| 4XX | Delete SSL Configuration response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_response_id_only](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-response-id-only.md)

## Security

- **api_email**
- **api_key**
- **api_token**
