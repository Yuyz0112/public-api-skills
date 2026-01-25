# POST /accounts/{account_id}/gateway/certificates

**Resource:** [Zero Trust certificates](../resources/Zero-Trust-certificates.md)
**Create Zero Trust certificate**
**Operation ID:** `zero-trust-certificates-create-zero-trust-certificate`

Create a new Zero Trust certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [zero-trust-gateway_generate-cert-request](../schemas/zero-trust-gateway/zero-trust-gateway-generate-cert-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Creates Zero Trust certificate response. |
| 4XX | Creates Zero Trust certificate response failure. |

**Success Response Schema:**

[zero-trust-gateway_single_response](../schemas/zero-trust-gateway/zero-trust-gateway-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
