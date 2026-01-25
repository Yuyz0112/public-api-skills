# DELETE /users/{id}/notification_rules/{notification_rule_id}

**Resource:** [Users](../resources/Users.md)
**Delete a user's notification rule**
**Operation ID:** `deleteUserNotificationRule`

Remove a user's notification rule.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users:contact_methods.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The notification rule was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

