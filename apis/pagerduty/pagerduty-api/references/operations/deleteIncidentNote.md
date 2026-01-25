# DELETE /incidents/{id}/notes/{note_id}

**Resource:** [Incidents](../resources/Incidents.md)
**Delete a note on an incident**
**Operation ID:** `deleteIncidentNote`

Delete an existing note for the specified incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | Note deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

