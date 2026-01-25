# GET /user/following

**Resource:** [users](../resources/users.md)
**List the people the authenticated user follows**
**Operation ID:** `users/list-followed-by-authenticated-user`

Lists the people who the authenticated user follows.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

