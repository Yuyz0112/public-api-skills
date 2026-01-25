# GET /incidents/{id}/alerts

**Resource:** [Incidents](../resources/Incidents.md)
**List alerts for an incident**
**Operation ID:** `listIncidentAlerts`

List alerts for the specified incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of the incident's alerts. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

