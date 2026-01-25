# PUT /users/{id}

**Resource:** [Users](../resources/Users.md)
**Update a user**
**Operation ID:** `updateUser`

Update an existing user.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.write`


## Request Body

The user to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The user that was updated. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

