# POST /accounts/{account_id}/addressing/prefixes/{prefix_id}/delegations

**Resource:** [IP Address Management Prefix Delegation](../resources/IP-Address-Management-Prefix-Delegation.md)
**Create Prefix Delegation**
**Operation ID:** `ip-address-management-prefix-delegation-create-prefix-delegation`

Create a new account delegation for a given IP prefix.

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
| 200 | Create Prefix Delegation response |
| 4XX | Create Prefix Delegation response failure |

**Success Response Schema:**

[addressing_schemas-single_response](../schemas/addressing/addressing-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
