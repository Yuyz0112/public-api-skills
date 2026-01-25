# GET /accounts/{account_id}/gateway/certificates

**Resource:** [Zero Trust certificates](../resources/Zero-Trust-certificates.md)
**List Zero Trust certificates**
**Operation ID:** `zero-trust-certificates-list-zero-trust-certificates`

List all Zero Trust certificates for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Lists Zero Trust certificates response. |
| 4XX | Lists Zero Trust certificates response failure. |

**Success Response Schema:**

[zero-trust-gateway_response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
