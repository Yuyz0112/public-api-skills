# GET /accounts/{account_id}/gateway/pacfiles

**Resource:** [Zero Trust Gateway PAC files](../resources/Zero-Trust-Gateway-PAC-files.md)
**List PAC files**
**Operation ID:** `zero-trust-gateway-pacfiles-list`

List all Zero Trust Gateway PAC files for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of PAC files response. |
| 4XX | Returns a list of PAC files response failure. |

**Success Response Schema:**

[zero-trust-gateway_pacfiles_components-schemas-response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-pacfiles-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
