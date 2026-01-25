# POST /zones/{zone_id}/acm/custom_trust_store

**Resource:** [Custom Origin Trust Store](../resources/Custom-Origin-Trust-Store.md)
**Upload Custom Origin Trust Store**
**Operation ID:** `custom-origin-trust-store-create`

Add Custom Origin Trust Store for a Zone.

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
| 200 | Upload Custom Origin Trust Store response |
| 4XX | Upload Custom Origin Trust Store response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_trust_store_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-trust-store-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
