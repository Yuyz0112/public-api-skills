# POST /teams/{id}/notification_subscriptions/unsubscribe

**Resource:** [Teams](../resources/Teams.md)
**Operation ID:** `removeTeamNotificationSubscriptions`

Unsubscribe the given Team from Notifications on the matching Subscribable entities.

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

