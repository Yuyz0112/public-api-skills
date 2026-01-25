# GET /user/blocks

**Resource:** [users](../resources/users.md)
**List users blocked by the authenticated user**
**Operation ID:** `users/list-blocked-by-authenticated-user`

List the users you've blocked on your personal account.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

