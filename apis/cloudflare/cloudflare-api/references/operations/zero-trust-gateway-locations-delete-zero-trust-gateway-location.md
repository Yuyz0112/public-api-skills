# DELETE /accounts/{account_id}/gateway/locations/{location_id}

**Resource:** [Zero Trust Gateway locations](../resources/Zero-Trust-Gateway-locations.md)
**Delete a Zero Trust Gateway location**
**Operation ID:** `zero-trust-gateway-locations-delete-zero-trust-gateway-location`

Delete a configured Zero Trust Gateway location.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `location_id` | path | zero-trust-gateway_components-schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Deletes a Zero Trust Gateway location response. |
| 4XX | Deletes a Zero Trust Gateway location response failure. |

**Success Response Schema:**

[zero-trust-gateway_empty_response](../schemas/zero-trust-gateway/zero-trust-gateway-empty-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
