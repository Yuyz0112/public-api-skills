# PATCH /accounts/{account_id}/addressing/address_maps/{address_map_id}

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Update Address Map**
**Operation ID:** `ip-address-management-address-maps-update-address-map`

Modify properties of an address map owned by the account.

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
| 200 | Update Address Map response |
| 4XX | Update Address Map response failure |

**Success Response Schema:**

[addressing_components-schemas-single_response](../schemas/addressing/addressing-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
