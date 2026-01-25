# GET /users

**Resource:** [users](../resources/users.md)
**List users**
**Operation ID:** `users/list`

Lists all users, in the order that they signed up on GitHub. This list includes personal user accounts and organization accounts.

Note: Pagination is powered exclusively by the `since` parameter. Use the [Link header](https://docs.github.com/rest/guides/using-pagination-in-the-rest-api#using-link-headers) to get the URL for the next page of users.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)

