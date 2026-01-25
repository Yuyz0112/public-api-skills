# POST /incidents/{id}/notes

**Resource:** [Incidents](../resources/Incidents.md)
**Create a note on an incident**
**Operation ID:** `createIncidentNote`

Create a new note for the specified incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

A maximum of 2000 notes can be added to an incident.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The new note. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

