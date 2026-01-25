# GET /users/{id}/contact_methods/{contact_method_id}

**Resource:** [Users](../resources/Users.md)
**Get a user's contact method**
**Operation ID:** `getUserContactMethod`

Get details about a User's contact method.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:contact_methods.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The user's contact method requested. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

