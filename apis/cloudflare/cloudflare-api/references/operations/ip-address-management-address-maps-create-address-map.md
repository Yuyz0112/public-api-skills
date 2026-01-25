# POST /accounts/{account_id}/addressing/address_maps

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**Create Address Map**
**Operation ID:** `ip-address-management-address-maps-create-address-map`

Create a new address map under the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Address Map response |
| 4XX | Create Address Map response failure |

**Success Response Schema:**

[addressing_full_response](../schemas/addressing/addressing-full-response.md)

## Security

- **api_email**
- **api_key**
