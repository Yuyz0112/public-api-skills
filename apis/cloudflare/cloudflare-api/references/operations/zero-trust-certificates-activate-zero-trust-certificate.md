# POST /accounts/{account_id}/gateway/certificates/{certificate_id}/activate

**Resource:** [Zero Trust certificates](../resources/Zero-Trust-certificates.md)
**Activate a Zero Trust certificate**
**Operation ID:** `zero-trust-certificates-activate-zero-trust-certificate`

Bind a single Zero Trust certificate to the edge.

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
| 202 | Activates Zero Trust certificate details response. |
| 4XX | Activates Zero Trust certificate details response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
