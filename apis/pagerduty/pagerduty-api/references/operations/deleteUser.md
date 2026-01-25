# DELETE /users/{id}

**Resource:** [Users](../resources/Users.md)
**Delete a user**
**Operation ID:** `deleteUser`

Remove an existing user.

Returns 400 if the user has assigned incidents unless your [pricing plan](https://www.pagerduty.com/pricing) has the `offboarding` feature and the account is [configured](https://support.pagerduty.com/docs/offboarding#section-additional-configurations) appropriately.

Note that the incidents reassignment process is asynchronous and has no guarantee to complete before the api call return.

[*Learn more about `offboarding` feature*](https://support.pagerduty.com/docs/offboarding).

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The user was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

