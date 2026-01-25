# PUT /incidents/{id}

**Resource:** [Incidents](../resources/Incidents.md)
**Update an incident**
**Operation ID:** `updateIncident`

Acknowledge, resolve, escalate or reassign an incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The incident was updated. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

