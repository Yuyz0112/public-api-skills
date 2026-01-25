# DELETE /zones/{zone_id}/keyless_certificates/{keyless_certificate_id}

**Resource:** [Keyless SSL for a Zone](../resources/Keyless-SSL-for-a-Zone.md)
**Delete Keyless SSL Configuration**
**Operation ID:** `keyless-ssl-for-a-zone-delete-keyless-ssl-configuration`

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
| 200 | Delete Keyless SSL Configuration response |
| 4XX | Delete Keyless SSL Configuration response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_keyless_response_single_id](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-keyless-response-single-id.md)

## Security

- **api_email**
- **api_key**
- **api_token**
