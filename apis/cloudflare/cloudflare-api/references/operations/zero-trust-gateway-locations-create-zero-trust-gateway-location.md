# POST /accounts/{account_id}/gateway/locations

**Resource:** [Zero Trust Gateway locations](../resources/Zero-Trust-Gateway-locations.md)
**Create a Zero Trust Gateway location**
**Operation ID:** `zero-trust-gateway-locations-create-zero-trust-gateway-location`

Create a new Zero Trust Gateway location.

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
| 200 | Creates a Zero Trust Gateway location response. |
| 4XX | Creates a Zero Trust Gateway location response failure. |

**Success Response Schema:**

[zero-trust-gateway_schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
