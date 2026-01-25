# PUT /accounts/{account_id}/registrar/domains/{domain_name}

**Resource:** [Registrar Domains](../resources/Registrar-Domains.md)
**Update domain**
**Operation ID:** `registrar-domains-update-domain`

Update individual domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain_name` | path | registrar-api_domain_name | Yes |  |
| `account_id` | path | registrar-api_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update domain response |
| 4XX | Update domain response failure |

**Success Response Schema:**

[registrar-api_domain_response_single](../schemas/registrar-api/registrar-api-domain-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
