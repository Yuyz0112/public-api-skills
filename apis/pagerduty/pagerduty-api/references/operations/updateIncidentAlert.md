# PUT /incidents/{id}/alerts/{alert_id}

**Resource:** [Incidents](../resources/Incidents.md)
**Update an alert**
**Operation ID:** `updateIncidentAlert`

Resolve an alert or associate an alert with a new parent incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

When a service sends an event to PagerDuty, an alert and corresponding incident is triggered in PagerDuty.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

The parameters of the alert to update.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The alert that was updated. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

