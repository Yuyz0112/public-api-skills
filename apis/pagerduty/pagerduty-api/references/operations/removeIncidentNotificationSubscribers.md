# POST /incidents/{id}/status_updates/unsubscribe

**Resource:** [Incidents](../resources/Incidents.md)
**Remove Notification Subscriber**
**Operation ID:** `removeIncidentNotificationSubscribers`

Unsubscribes the matching Subscribers from Incident Status Update Notifications.

Scoped OAuth requires: `subscribers.write`


## Request Body

The entities to unsubscribe.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

