# DELETE /users/{id}/oncall_handoff_notification_rules/{oncall_handoff_notification_rule_id}

**Resource:** [Users](../resources/Users.md)
**Delete a User's Handoff Notification rule**
**Operation ID:** `deleteUserHandoffNotificationRule`

Remove a User's Handoff Notification Rule.
Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.
For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The handoff notification rule was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

