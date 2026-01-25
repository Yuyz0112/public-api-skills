# DELETE /accounts/{account_id}/addressing/address_maps/{address_map_id}/zones/{zone_id}

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Remove a zone membership from an Address Map**
**Operation ID:** `ip-address-management-address-maps-remove-a-zone-membership-from-an-address-map`

Remove a zone as a member of a particular address map.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | addressing_zone_identifier | Yes |  |
| `address_map_id` | path | addressing_address_map_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Remove a zone membership from an Address Map response |
| 4XX | Remove a zone membership from an Address Map response failure |

**Success Response Schema:**

[addressing_api-response-collection](../schemas/addressing/addressing-api-response-collection.md)

## Security

- **api_email**
- **api_key**
