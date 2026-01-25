# DELETE /zones/{zone_id}/acm/custom_trust_store/{custom_origin_trust_store_id}

**Resource:** [Custom Origin Trust Store](../resources/Custom-Origin-Trust-Store.md)
**Delete Custom Origin Trust Store**
**Operation ID:** `custom-origin-trust-store-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_origin_trust_store_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Custom Origin Trust Store response |
| 4XX | Delete Custom Origin Trust Store response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_trust_store_response_id_only](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-trust-store-response-id-only.md)

## Security

- **api_email**
- **api_key**
- **api_token**
