# GET /users/{id}/notification_subscriptions

**Resource:** [Users](../resources/Users.md)
**List Notification Subscriptions**
**Operation ID:** `getUserNotificationSubscriptions`

Retrieve a list of Notification Subscriptions the given User has.

<!-- theme: warning -->
> Users must be added through `POST /users/{id}/notification_subscriptions` to be returned from this endpoint.

Scoped OAuth requires: `subscribers.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

