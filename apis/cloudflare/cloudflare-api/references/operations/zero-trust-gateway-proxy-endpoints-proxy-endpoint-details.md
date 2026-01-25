# GET /accounts/{account_id}/gateway/proxy_endpoints/{proxy_endpoint_id}

**Resource:** [Zero Trust Gateway proxy endpoints](../resources/Zero-Trust-Gateway-proxy-endpoints.md)
**Get a proxy endpoint**
**Operation ID:** `zero-trust-gateway-proxy-endpoints-proxy-endpoint-details`

Get a single Zero Trust Gateway proxy endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `proxy_endpoint_id` | path | zero-trust-gateway_components-schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a proxy endpoint response. |
| 4XX | Returns a proxy endpoint response failure. |

**Success Response Schema:**

[zero-trust-gateway_proxy-endpoints_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-proxy-endpoints-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
