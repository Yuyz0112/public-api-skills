# GET /accounts/{account_id}/gateway/locations

**Resource:** [Zero Trust Gateway locations](../resources/Zero-Trust-Gateway-locations.md)
**List Zero Trust Gateway locations**
**Operation ID:** `zero-trust-gateway-locations-list-zero-trust-gateway-locations`

List Zero Trust Gateway locations for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Lists Zero Trust Gateway locations response. |
| 4XX | Lists Zero Trust Gateway locations response failure. |

**Success Response Schema:**

[zero-trust-gateway_components-schemas-response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
