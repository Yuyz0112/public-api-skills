# GET /users/{id}/sessions/{type}/{session_id}

**Resource:** [Users](../resources/Users.md)
**Get a user's session**
**Operation ID:** `getUserSession`

Get details about a user's session.

Beginning November 2021, user sessions no longer includes newly issued OAuth tokens.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:sessions.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The user's session requested. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

