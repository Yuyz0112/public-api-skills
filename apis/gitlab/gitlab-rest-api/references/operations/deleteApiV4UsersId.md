# DELETE /api/v4/users/{id}

**Resource:** [Users](../resources/Users.md)
**Delete a user. Available only for admins.**
**Operation ID:** `deleteApiV4UsersId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `hard_delete` | query | boolean | No | Whether to remove a user's contributions |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

