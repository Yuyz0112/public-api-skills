# GET /users/{id}/oncall_handoff_notification_rules

**Resource:** [Users](../resources/Users.md)
**List a User's Handoff Notification Rules**
**Operation ID:** `getUserHandoffNotificationRules`

List Handoff Notification Rules of your PagerDuty User.
Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.
For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of Handoff Notification Rules. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

