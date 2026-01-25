# PUT /user/blocks/{username}

**Resource:** [users](../resources/users.md)
**Block a user**
**Operation ID:** `users/block`

Blocks the given user and returns a 204. If the authenticated user cannot block the given user a 422 is returned.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

