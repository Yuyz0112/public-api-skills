# GET /incidents/{id}/past_incidents

**Resource:** [Incidents](../resources/Incidents.md)
**Get Past Incidents**
**Operation ID:** `getPastIncidents`

Past Incidents returns Incidents within the past 6 months that have similar metadata and were generated on the same Service as the parent Incident. By default, 5 Past Incidents are returned. Note: This feature is currently available as part of the Event Intelligence package or Digital Operations plan only.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#past_incidents)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

