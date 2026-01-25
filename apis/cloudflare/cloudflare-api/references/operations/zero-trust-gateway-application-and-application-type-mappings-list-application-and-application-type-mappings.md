# GET /accounts/{account_id}/gateway/app_types

**Resource:** [Zero Trust Gateway application and application type mappings](../resources/Zero-Trust-Gateway-application-and-application-type-mappings.md)
**List application and application type mappings**
**Operation ID:** `zero-trust-gateway-application-and-application-type-mappings-list-application-and-application-type-mappings`

List all application and application type mappings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List application and application type mappings response. |
| 4XX | List application and application type mappings response failure. |

**Success Response Schema:**

[zero-trust-gateway_app-types_components-schemas-response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-app-types-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
