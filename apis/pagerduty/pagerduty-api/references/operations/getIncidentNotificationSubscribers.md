# GET /incidents/{id}/status_updates/subscribers

**Resource:** [Incidents](../resources/Incidents.md)
**List Notification Subscribers**
**Operation ID:** `getIncidentNotificationSubscribers`

Retrieve a list of Notification Subscribers on the Incident.

<!-- theme: warning -->
> Users must be added through `POST /incident/{id}/status_updates/subscribers` to be returned from this endpoint.
Scoped OAuth requires: `subscribers.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |
| 429 | (reference) |

