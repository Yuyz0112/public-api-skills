# PATCH /zones/{zone_id}/keyless_certificates/{keyless_certificate_id}

**Resource:** [Keyless SSL for a Zone](../resources/Keyless-SSL-for-a-Zone.md)
**Edit Keyless SSL Configuration**
**Operation ID:** `keyless-ssl-for-a-zone-edit-keyless-ssl-configuration`

This will update attributes of a Keyless SSL. Consists of one or more of the following:  host,name,port.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `keyless_certificate_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit Keyless SSL Configuration response |
| 4XX | Edit Keyless SSL Configuration response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_keyless_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-keyless-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
