# DELETE /accounts/{account_id}/gateway/proxy_endpoints/{proxy_endpoint_id}

**Resource:** [Zero Trust Gateway proxy endpoints](../resources/Zero-Trust-Gateway-proxy-endpoints.md)
**Delete a proxy endpoint**
**Operation ID:** `zero-trust-gateway-proxy-endpoints-delete-proxy-endpoint`

Delete a configured Zero Trust Gateway proxy endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `proxy_endpoint_id` | path | zero-trust-gateway_components-schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a deleted proxy endpoint response. |
| 4XX | Returns a deleted proxy endpoint response failure. |

**Success Response Schema:**

[zero-trust-gateway_empty_response](../schemas/zero-trust-gateway/zero-trust-gateway-empty-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
