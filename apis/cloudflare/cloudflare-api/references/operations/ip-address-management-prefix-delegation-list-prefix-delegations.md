# GET /accounts/{account_id}/addressing/prefixes/{prefix_id}/delegations

**Resource:** [IP Address Management Prefix Delegation](../resources/IP-Address-Management-Prefix-Delegation.md)
**List Prefix Delegations**
**Operation ID:** `ip-address-management-prefix-delegation-list-prefix-delegations`

List all delegations for a given account IP prefix.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Prefix Delegations response |
| 4XX | List Prefix Delegations response failure |

**Success Response Schema:**

[addressing_schemas-response_collection](../schemas/addressing/addressing-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
