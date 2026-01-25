# DELETE /accounts/{account_id}/addressing/address_maps/{address_map_id}/ips/{ip_address}

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Remove an IP from an Address Map**
**Operation ID:** `ip-address-management-address-maps-remove-an-ip-from-an-address-map`

Remove an IP from a particular address map.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ip_address` | path | addressing_ip_address | Yes |  |
| `address_map_id` | path | addressing_address_map_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Remove an IP from an Address Map response |
| 4XX | Remove an IP from an Address Map response failure |

**Success Response Schema:**

[addressing_api-response-collection](../schemas/addressing/addressing-api-response-collection.md)

## Security

- **api_email**
- **api_key**
