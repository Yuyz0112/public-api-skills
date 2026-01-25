# DELETE /accounts/{account_id}/addressing/address_maps/{address_map_id}/accounts/{account_id}

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Remove an account membership from an Address Map**
**Operation ID:** `ip-address-management-address-maps-remove-an-account-membership-from-an-address-map`

Remove an account as a member of a particular address map.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `address_map_id` | path | addressing_address_map_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Remove an account membership from an Address Map response |
| 4XX | Remove an account membership from an Address Map response failure |

**Success Response Schema:**

[addressing_api-response-collection](../schemas/addressing/addressing-api-response-collection.md)

## Security

- **api_email**
- **api_key**
