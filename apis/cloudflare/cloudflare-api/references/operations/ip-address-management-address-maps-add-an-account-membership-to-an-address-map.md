# PUT /accounts/{account_id}/addressing/address_maps/{address_map_id}/accounts/{account_id}

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Add an account membership to an Address Map**
**Operation ID:** `ip-address-management-address-maps-add-an-account-membership-to-an-address-map`

Add an account as a member of a particular address map.

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
| 200 | Add an account membership to an Address Map response |
| 4XX | Add an account membership to an Address Map response failure |

**Success Response Schema:**

[addressing_api-response-collection](../schemas/addressing/addressing-api-response-collection.md)

## Security

- **api_email**
- **api_key**
