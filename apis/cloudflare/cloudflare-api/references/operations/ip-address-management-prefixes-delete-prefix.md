# DELETE /accounts/{account_id}/addressing/prefixes/{prefix_id}

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**Delete Prefix**
**Operation ID:** `ip-address-management-prefixes-delete-prefix`

Delete an unapproved prefix owned by the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Prefix response |
| 4XX | Delete Prefix response failure |

**Success Response Schema:**

[addressing_api-response-single](../schemas/addressing/addressing-api-response-single.md)

## Security

- **api_email**
- **api_key**
