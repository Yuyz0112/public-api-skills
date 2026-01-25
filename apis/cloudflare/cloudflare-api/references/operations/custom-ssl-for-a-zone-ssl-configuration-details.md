# GET /zones/{zone_id}/custom_certificates/{custom_certificate_id}

**Resource:** [Custom SSL for a Zone](../resources/Custom-SSL-for-a-Zone.md)
**SSL Configuration Details**
**Operation ID:** `custom-ssl-for-a-zone-ssl-configuration-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | SSL Configuration Details response |
| 4XX | SSL Configuration Details response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
