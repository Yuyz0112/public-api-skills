# POST /users/{id}/contact_methods

**Resource:** [Users](../resources/Users.md)
**Create a user contact method**
**Operation ID:** `createUserContactMethod`

Create a new contact method for the User.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:contact_methods.write`


## Request Body

The contact method to be created.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The contact method that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

