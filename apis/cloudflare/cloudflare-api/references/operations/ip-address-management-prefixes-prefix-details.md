# GET /accounts/{account_id}/addressing/prefixes/{prefix_id}

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**Prefix Details**
**Operation ID:** `ip-address-management-prefixes-prefix-details`

List a particular prefix owned by the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Prefix Details response |
| 4XX | Prefix Details response failure |

**Success Response Schema:**

[addressing_single_response](../schemas/addressing/addressing-single-response.md)

## Security

- **api_email**
- **api_key**
