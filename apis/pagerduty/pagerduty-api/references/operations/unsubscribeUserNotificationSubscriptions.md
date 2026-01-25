# POST /users/{id}/notification_subscriptions/unsubscribe

**Resource:** [Users](../resources/Users.md)
**Remove Notification Subscriptions**
**Operation ID:** `unsubscribeUserNotificationSubscriptions`

Unsubscribe the given User from Notifications on the matching Subscribable entities.

Scoped OAuth requires: `subscribers.write`


## Request Body

The entities to unsubscribe from.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

