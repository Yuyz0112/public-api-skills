# GET /accounts/{account_id}/addressing/address_maps

**Resource:** [IP Address Management Address Maps](../resources/IP-Address-Management-Address-Maps.md)
**List Address Maps**
**Operation ID:** `ip-address-management-address-maps-list-address-maps`

List all address maps owned by the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Address Maps response |
| 4XX | List Address Maps response failure |

**Success Response Schema:**

[addressing_components-schemas-response_collection](../schemas/addressing/addressing-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
