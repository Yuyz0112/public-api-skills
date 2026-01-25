# POST /users/{id}/status_update_notification_rules

**Resource:** [Users](../resources/Users.md)
**Create a user status update notification rule**
**Operation ID:** `createUserStatusUpdateNotificationRule`

Create a new status update notification rule.

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.write`


## Request Body

The status update notification rule to be created.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The status update notification rule that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

