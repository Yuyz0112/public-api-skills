# GET /user/followers

**Resource:** [users](../resources/users.md)
**List followers of the authenticated user**
**Operation ID:** `users/list-followers-for-authenticated-user`

Lists the people following the authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

