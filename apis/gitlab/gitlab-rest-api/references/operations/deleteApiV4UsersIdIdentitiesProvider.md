# DELETE /api/v4/users/{id}/identities/{provider}

**Resource:** [Users](../resources/Users.md)
**Delete a user's identity. Available only for admins**
**Operation ID:** `deleteApiV4UsersIdIdentitiesProvider`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `provider` | path | string | Yes | The external provider |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

