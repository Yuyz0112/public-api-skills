# DELETE /accounts/{account_id}/addressing/prefixes/{prefix_id}/delegations/{delegation_id}

**Resource:** [IP Address Management Prefix Delegation](../resources/IP-Address-Management-Prefix-Delegation.md)
**Delete Prefix Delegation**
**Operation ID:** `ip-address-management-prefix-delegation-delete-prefix-delegation`

Delete an account delegation for a given IP prefix.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `delegation_id` | path | addressing_delegation_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Prefix Delegation response |
| 4XX | Delete Prefix Delegation response failure |

**Success Response Schema:**

[addressing_id_response](../schemas/addressing/addressing-id-response.md)

## Security

- **api_email**
- **api_key**
