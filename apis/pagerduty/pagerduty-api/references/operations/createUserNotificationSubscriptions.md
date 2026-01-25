# POST /users/{id}/notification_subscriptions

**Resource:** [Users](../resources/Users.md)
**Create Notification Subcriptions**
**Operation ID:** `createUserNotificationSubscriptions`

Create new Notification Subscriptions for the given User.

Scoped OAuth requires: `subscribers.write`


## Request Body

The entities to subscribe to.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

