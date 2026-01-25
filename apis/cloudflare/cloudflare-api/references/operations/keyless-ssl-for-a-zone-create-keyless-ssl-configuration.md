# POST /zones/{zone_id}/keyless_certificates

**Resource:** [Keyless SSL for a Zone](../resources/Keyless-SSL-for-a-Zone.md)
**Create Keyless SSL Configuration**
**Operation ID:** `keyless-ssl-for-a-zone-create-keyless-ssl-configuration`

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
| 200 | Create Keyless SSL Configuration response |
| 4XX | Create Keyless SSL Configuration response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_keyless_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-keyless-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
