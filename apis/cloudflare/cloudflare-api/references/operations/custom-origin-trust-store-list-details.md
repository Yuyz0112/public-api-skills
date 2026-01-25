# GET /zones/{zone_id}/acm/custom_trust_store

**Resource:** [Custom Origin Trust Store](../resources/Custom-Origin-Trust-Store.md)
**List Custom Origin Trust Store Details**
**Operation ID:** `custom-origin-trust-store-list-details`

Get Custom Origin Trust Store for a Zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `limit` | query | integer | No |  |
| `offset` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Custom Origin Trust Store Details response |
| 4XX | Custom Origin Trust Store response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_trust_store_response_collection](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-trust-store-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
