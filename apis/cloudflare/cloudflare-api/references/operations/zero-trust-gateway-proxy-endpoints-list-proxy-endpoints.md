# GET /accounts/{account_id}/gateway/proxy_endpoints

**Resource:** [Zero Trust Gateway proxy endpoints](../resources/Zero-Trust-Gateway-proxy-endpoints.md)
**List proxy endpoints**
**Operation ID:** `zero-trust-gateway-proxy-endpoints-list-proxy-endpoints`

List all Zero Trust Gateway proxy endpoints for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of proxy endpoints response. |
| 4XX | Returns a list of proxy endpoints response failure. |

**Success Response Schema:**

[zero-trust-gateway_proxy-endpoints_components-schemas-response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-proxy-endpoints-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
