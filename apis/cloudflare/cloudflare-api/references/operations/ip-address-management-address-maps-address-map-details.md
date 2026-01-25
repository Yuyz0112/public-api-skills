# GET /accounts/{account_id}/addressing/address_maps/{address_map_id}

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Address Map Details**
**Operation ID:** `ip-address-management-address-maps-address-map-details`

Show a particular address map owned by the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `address_map_id` | path | addressing_address_map_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Address Map Details response |
| 4XX | Address Map Details response failure |

**Success Response Schema:**

[addressing_full_response](../schemas/addressing/addressing-full-response.md)

## Security

- **api_email**
- **api_key**
