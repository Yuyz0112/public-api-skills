# POST /users/{id}/oncall_handoff_notification_rules

**Resource:** [Users](../resources/Users.md)
**Create a User Handoff Notification Rule**
**Operation ID:** `createUserHandoffNotificationRule`

Create a new Handoff Notification Rule.
Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.
For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.write`


## Request Body

The Handoff Notification Rule to be created.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The Handoff Notification Rule that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

