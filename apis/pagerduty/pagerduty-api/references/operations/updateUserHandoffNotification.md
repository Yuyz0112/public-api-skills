# PUT /users/{id}/oncall_handoff_notification_rules/{oncall_handoff_notification_rule_id}

**Resource:** [Users](../resources/Users.md)
**Update a User's Handoff Notification Rule**
**Operation ID:** `updateUserHandoffNotification`

Update a User's Handoff Notification Rule.
Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.
For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#users)

Scoped OAuth requires: `users.write`


## Request Body

The User's Handoff Notification Rule to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The User's Handoff Notification Rule that was updated. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

