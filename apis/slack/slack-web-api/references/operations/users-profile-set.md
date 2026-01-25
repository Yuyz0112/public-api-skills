# POST /users.profile.set

**Resource:** [users.profile](../resources/users-profile.md)
**Operation ID:** `users_profile_set`

Set the profile information for a user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `users.profile:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: users.profile:write
