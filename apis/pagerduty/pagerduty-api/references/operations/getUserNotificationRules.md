# GET /users/{id}/notification_rules

**Resource:** [Users](../resources/Users.md)
**List a user's notification rules**
**Operation ID:** `getUserNotificationRules`

List notification rules of your PagerDuty user.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:contact_methods.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of notification rules. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

