# GET /teams/{id}/notification_subscriptions

**Resource:** [Teams](../resources/Teams.md)
**List Team Notification Subscriptions**
**Operation ID:** `getTeamNotificationSubscriptions`

Retrieve a list of Notification Subscriptions the given Team has.

<!-- theme: warning -->
> Teams must be added through `POST /teams/{id}/notification_subscriptions` to be returned from this endpoint.

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

