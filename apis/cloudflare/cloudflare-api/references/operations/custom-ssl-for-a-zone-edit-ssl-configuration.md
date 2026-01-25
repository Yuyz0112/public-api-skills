# PATCH /zones/{zone_id}/custom_certificates/{custom_certificate_id}

**Resource:** [Custom SSL for a Zone](../resources/Custom-SSL-for-a-Zone.md)
**Edit SSL Configuration**
**Operation ID:** `custom-ssl-for-a-zone-edit-ssl-configuration`

Upload a new private key and/or PEM/CRT for the SSL certificate. Note: PATCHing a configuration for sni_custom certificates will result in a new resource id being returned, and the previous one being deleted.

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
| 200 | Edit SSL Configuration response |
| 4XX | Edit SSL Configuration response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
