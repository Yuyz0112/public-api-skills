# GET /incidents/{id}

**Resource:** [Incidents](../resources/Incidents.md)
**Get an incident**
**Operation ID:** `getIncident`

Show detailed information about an incident. Accepts either an incident id, or an incident number.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The incident requested. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

