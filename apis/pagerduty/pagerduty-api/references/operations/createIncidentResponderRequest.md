# POST /incidents/{id}/responder_requests

**Resource:** [Incidents](../resources/Incidents.md)
**Create a responder request for an incident**
**Operation ID:** `createIncidentResponderRequest`

Send a new responder request for the specified incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The new responder request for the given incident. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

