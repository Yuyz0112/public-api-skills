# GET /user/blocks/{username}

**Resource:** [users](../resources/users.md)
**Check if a user is blocked by the authenticated user**
**Operation ID:** `users/check-blocked`

Returns a 204 if the given user is blocked by the authenticated user. Returns a 404 if the given user is not blocked by the authenticated user, or if the given user account has been identified as spam by GitHub.

## Responses

| Status | Description |
|--------|-------------|
| 204 | If the user is blocked |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | If the user is not blocked |

