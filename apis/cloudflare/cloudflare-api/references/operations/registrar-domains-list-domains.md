# GET /accounts/{account_id}/registrar/domains

**Resource:** [Registrar Domains](../resources/Registrar-Domains.md)
**List domains**
**Operation ID:** `registrar-domains-list-domains`

List domains handled by Registrar.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | registrar-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List domains response |
| 4XX | List domains response failure |

**Success Response Schema:**

[registrar-api_domain_response_collection](../schemas/registrar-api/registrar-api-domain-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
