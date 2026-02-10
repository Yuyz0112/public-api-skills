# DELETE /api/v4/groups/{id}/service_accounts/{user_id}

**Resource:** [Service accounts](../resources/Service-accounts.md)
**Delete a service account user. Available only for group owners and admins.**
**Operation ID:** `deleteApiV4GroupsIdServiceAccountsUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `user_id` | path | integer | Yes | The ID of the service account user |
| `hard_delete` | query | boolean | No | Whether to remove a user's contributions |

## Responses

| Status | Description |
|--------|-------------|
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Group not found |

