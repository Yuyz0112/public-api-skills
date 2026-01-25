# GET /incidents/{id}/related_incidents

**Resource:** [Incidents](../resources/Incidents.md)
**Get Related Incidents**
**Operation ID:** `getRelatedIncidents`

Returns the 20 most recent Related Incidents that are impacting other Responders and Services. Note: This feature is currently available as part of the Event Intelligence package or Digital Operations plan only.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#related_incidents)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of Related Incidents and their relationships. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

