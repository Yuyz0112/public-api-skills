# GET /accounts/{account_id}/addressing/leases

**Resource:** [IP Address Management Leases](../resources/IP-Address-Management-Leases.md)
**List Leases**
**Operation ID:** `ip-address-management-list-leases`

List all leases owned by the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_schemas-account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Leases response |
| 4XX | List Leases response failure |

**Success Response Schema:**

[addressing_leases_components-schemas-response_collection](../schemas/addressing/addressing-leases-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
