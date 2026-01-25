# GET /accounts/{account_id}/gateway/certificates/{certificate_id}

**Resource:** [Zero Trust certificates](../resources/Zero-Trust-certificates.md)
**Get Zero Trust certificate details**
**Operation ID:** `zero-trust-certificates-zero-trust-certificate-details`

Get a single Zero Trust certificate.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | zero-trust-gateway_uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Gets Zero Trust certificate details response. |
| 4XX | Gets Zero Trust certificate details response failure. |

**Success Response Schema:**

[zero-trust-gateway_single_response](../schemas/zero-trust-gateway/zero-trust-gateway-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
