# GET /users/{username}/following

**Resource:** [users](../resources/users.md)
**List the people a user follows**
**Operation ID:** `users/list-following-for-user`

Lists the people who the specified user follows.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

