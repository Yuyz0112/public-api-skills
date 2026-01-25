# GET /accounts/{account_id}/gateway/locations/{location_id}

**Resource:** [Zero Trust Gateway locations](../resources/Zero-Trust-Gateway-locations.md)
**Get Zero Trust Gateway location details**
**Operation ID:** `zero-trust-gateway-locations-zero-trust-gateway-location-details`

Get a single Zero Trust Gateway location.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `location_id` | path | zero-trust-gateway_components-schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Gets Zero Trust Gateway location details response. |
| 4XX | Gets Zero Trust Gateway location details response failure. |

**Success Response Schema:**

[zero-trust-gateway_schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
