# POST /users.deletePhoto

**Resource:** [users](../resources/users.md)
**Operation ID:** `users_deletePhoto`

Delete the user profile photo

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: users.profile:write
