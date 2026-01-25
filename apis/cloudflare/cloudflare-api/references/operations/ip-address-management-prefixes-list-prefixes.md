# GET /accounts/{account_id}/addressing/prefixes

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**List Prefixes**
**Operation ID:** `ip-address-management-prefixes-list-prefixes`

List all prefixes owned by the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Prefixes response |
| 4XX | List Prefixes response failure |

**Success Response Schema:**

[addressing_response_collection](../schemas/addressing/addressing-response-collection.md)

## Security

- **api_email**
- **api_key**
