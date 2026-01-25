# POST /accounts/{account_id}/gateway/certificates/{certificate_id}/deactivate

**Resource:** [Zero Trust certificates](../resources/Zero-Trust-certificates.md)
**Deactivate a Zero Trust certificate**
**Operation ID:** `zero-trust-certificates-deactivate-zero-trust-certificate`

Unbind a single Zero Trust certificate from the edge.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | zero-trust-gateway_uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Deactivate Zero Trust certificate details response. |
| 4XX | Deactivate Zero Trust certificate details response failure. |

**Success Response Schema:**

[zero-trust-gateway_single_response](../schemas/zero-trust-gateway/zero-trust-gateway-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
