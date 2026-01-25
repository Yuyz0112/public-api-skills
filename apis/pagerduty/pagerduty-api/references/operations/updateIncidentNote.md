# PUT /incidents/{id}/notes/{note_id}

**Resource:** [Incidents](../resources/Incidents.md)
**Update a note on an incident**
**Operation ID:** `updateIncidentNote`

Update an existing note for the specified incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The updated note. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

