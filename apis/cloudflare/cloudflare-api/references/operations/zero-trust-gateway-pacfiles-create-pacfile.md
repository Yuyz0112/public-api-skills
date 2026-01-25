# POST /accounts/{account_id}/gateway/pacfiles

**Resource:** [Zero Trust Gateway PAC files](../resources/Zero-Trust-Gateway-PAC-files.md)
**Create a PAC file**
**Operation ID:** `zero-trust-gateway-pacfiles-create-pacfile`

Create a new Zero Trust Gateway PAC file.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a created PAC file response. |
| 4XX | Returns a created PAC file response failure. |

**Success Response Schema:**

[zero-trust-gateway_pacfiles_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-pacfiles-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
