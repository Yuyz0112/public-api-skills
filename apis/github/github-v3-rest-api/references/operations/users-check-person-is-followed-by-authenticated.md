# GET /user/following/{username}

**Resource:** [users](../resources/users.md)
**Check if a person is followed by the authenticated user**
**Operation ID:** `users/check-person-is-followed-by-authenticated`

## Responses

| Status | Description |
|--------|-------------|
| 204 | if the person is followed by the authenticated user |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | if the person is not followed by the authenticated user |

