# DELETE /accounts/{account_id}/access/policies/{policy_id}

**Resource:** [Access reusable policies](../resources/Access-reusable-policies.md)
**Delete an Access reusable policy**
**Operation ID:** `access-policies-delete-an-access-reusable-policy`

Deletes an Access reusable policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `policy_id` | path | access_schemas-uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete an Access reusable policy response. |
| 4XX | Delete an Access reusable policy response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
