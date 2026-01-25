# POST /accounts/{account_id}/gateway/proxy_endpoints

**Resource:** [Zero Trust Gateway proxy endpoints](../resources/Zero-Trust-Gateway-proxy-endpoints.md)
**Create a proxy endpoint**
**Operation ID:** `zero-trust-gateway-proxy-endpoints-create-proxy-endpoint`

Create a new Zero Trust Gateway proxy endpoint.

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
| 200 | Returns a created proxy endpoint response. |
| 4XX | Returns a created proxy endpoint response failure. |

**Success Response Schema:**

[zero-trust-gateway_proxy-endpoints_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-proxy-endpoints-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
