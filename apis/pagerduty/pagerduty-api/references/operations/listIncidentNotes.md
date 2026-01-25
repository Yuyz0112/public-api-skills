# GET /incidents/{id}/notes

**Resource:** [Incidents](../resources/Incidents.md)
**List notes for an incident**
**Operation ID:** `listIncidentNotes`

List existing notes for the specified incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of notes. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

