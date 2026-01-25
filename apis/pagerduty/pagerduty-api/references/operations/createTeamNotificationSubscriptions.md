# POST /teams/{id}/notification_subscriptions

**Resource:** [Teams](../resources/Teams.md)
**Create Team Notification Subscriptions**
**Operation ID:** `createTeamNotificationSubscriptions`

Create new Notification Subscriptions for the given Team.

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

