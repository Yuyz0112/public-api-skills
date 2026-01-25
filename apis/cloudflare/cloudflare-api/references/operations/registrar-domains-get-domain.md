# GET /accounts/{account_id}/registrar/domains/{domain_name}

**Resource:** [Registrar Domains](../resources/Registrar-Domains.md)
**Get domain**
**Operation ID:** `registrar-domains-get-domain`

Show individual domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain_name` | path | registrar-api_domain_name | Yes |  |
| `account_id` | path | registrar-api_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get domain response |
| 4XX | Get domain response failure |

**Success Response Schema:**

[registrar-api_domain_response_single](../schemas/registrar-api/registrar-api-domain-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
