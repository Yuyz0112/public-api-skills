# POST /zones/{zone_id}/custom_certificates

**Resource:** [Custom SSL for a Zone](../resources/Custom-SSL-for-a-Zone.md)
**Create SSL Configuration**
**Operation ID:** `custom-ssl-for-a-zone-create-ssl-configuration`

Upload a new SSL certificate for a zone.

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
| 200 | Create SSL Configuration response |
| 4XX | Create SSL Configuration response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_certificate_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-certificate-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
