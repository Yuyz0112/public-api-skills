# POST /incidents/{id}/status_updates

**Resource:** [Incidents](../resources/Incidents.md)
**Create a status update on an incident**
**Operation ID:** `createIncidentStatusUpdate`

Create a new status update for the specified incident. Optionally pass `subject` and `html_message` properties in the request body to override the email notification that gets sent.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The new status update for the specified incident. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

