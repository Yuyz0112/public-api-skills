# GET /users/{id}/notification_rules/{notification_rule_id}

**Resource:** [Users](../resources/Users.md)
**Get a user's notification rule**
**Operation ID:** `getUserNotificationRule`

Get details about a user's notification rule.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:contact_methods.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The user's notification rule requested. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

