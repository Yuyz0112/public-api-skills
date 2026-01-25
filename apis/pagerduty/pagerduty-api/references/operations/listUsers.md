# GET /users

**Resource:** [Users](../resources/Users.md)
**List users**
**Operation ID:** `listUsers`

List users of your PagerDuty account, optionally filtered by a search query.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of users. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

