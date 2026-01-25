# POST /incidents/{id}/status_updates/subscribers

**Resource:** [Incidents](../resources/Incidents.md)
**Add Notification Subscribers**
**Operation ID:** `createIncidentNotificationSubscribers`

Subscribe the given entities to Incident Status Update Notifications.

Scoped OAuth requires: `subscribers.write`


## Request Body

The entities to subscribe.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

