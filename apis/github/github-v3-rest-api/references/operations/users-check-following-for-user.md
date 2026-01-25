# GET /users/{username}/following/{target_user}

**Resource:** [users](../resources/users.md)
**Check if a user follows another user**
**Operation ID:** `users/check-following-for-user`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `target_user` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | if the user follows the target user |
| 404 | if the user does not follow the target user |

