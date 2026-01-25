# GET /users.profile.get

**Resource:** [users.profile](../resources/users-profile.md)
**Operation ID:** `users_profile_get`

Retrieves a user's profile information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `users.profile:read` |
| `include_labels` | query | boolean | No | Include labels for each ID in custom profile fields |
| `user` | query | string | No | User to retrieve profile info for |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: users.profile:read
