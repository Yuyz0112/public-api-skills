# GET /zones/{zone_id}/keyless_certificates/{keyless_certificate_id}

**Resource:** [Keyless SSL for a Zone](../resources/Keyless-SSL-for-a-Zone.md)
**Get Keyless SSL Configuration**
**Operation ID:** `keyless-ssl-for-a-zone-get-keyless-ssl-configuration`

Get details for one Keyless SSL configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `keyless_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Keyless SSL Configuration response |
| 4XX | Get Keyless SSL Configuration response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_keyless_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-keyless-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
