# GET /zones/{zone_id}/keyless_certificates

**Resource:** [Keyless SSL for a Zone](../resources/Keyless-SSL-for-a-Zone.md)
**List Keyless SSL Configurations**
**Operation ID:** `keyless-ssl-for-a-zone-list-keyless-ssl-configurations`

List all Keyless SSL configurations for a given zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Keyless SSL Configurations response |
| 4XX | List Keyless SSL Configurations response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_keyless_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-keyless-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
