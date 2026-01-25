# GET /users/{id}/sessions

**Resource:** [Users](../resources/Users.md)
**List a user's active sessions**
**Operation ID:** `getUserSessions`

List active sessions of a PagerDuty user.

Beginning November 2021, active sessions no longer includes newly issued OAuth tokens.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:sessions.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of the user's active sessions. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

