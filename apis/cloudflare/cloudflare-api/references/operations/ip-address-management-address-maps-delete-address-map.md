# DELETE /accounts/{account_id}/addressing/address_maps/{address_map_id}

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Delete Address Map**
**Operation ID:** `ip-address-management-address-maps-delete-address-map`

Delete a particular address map owned by the account. An Address Map must be disabled before it can be deleted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `address_map_id` | path | addressing_address_map_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Address Map response |
| 4XX | Delete Address Map response failure |

**Success Response Schema:**

[addressing_api-response-collection](../schemas/addressing/addressing-api-response-collection.md)

## Security

- **api_email**
- **api_key**
