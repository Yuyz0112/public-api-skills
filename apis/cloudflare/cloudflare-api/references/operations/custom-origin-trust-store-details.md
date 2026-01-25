# GET /zones/{zone_id}/acm/custom_trust_store/{custom_origin_trust_store_id}

**Resource:** [Custom Origin Trust Store](../resources/Custom-Origin-Trust-Store.md)
**Custom Origin Trust Store Details**
**Operation ID:** `custom-origin-trust-store-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_origin_trust_store_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Custom Origin Trust Store Details response |
| 4XX | Custom Origin Trust Store Details response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_trust_store_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-trust-store-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
