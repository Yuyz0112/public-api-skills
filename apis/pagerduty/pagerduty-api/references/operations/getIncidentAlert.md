# GET /incidents/{id}/alerts/{alert_id}

**Resource:** [Incidents](../resources/Incidents.md)
**Get an alert**
**Operation ID:** `getIncidentAlert`

Show detailed information about an alert. Accepts an alert id.

An incident represents a problem or an issue that needs to be addressed and resolved.

When a service sends an event to PagerDuty, an alert and corresponding incident is triggered in PagerDuty.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The alert requested. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

