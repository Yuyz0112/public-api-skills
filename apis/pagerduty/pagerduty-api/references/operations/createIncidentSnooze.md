# POST /incidents/{id}/snooze

**Resource:** [Incidents](../resources/Incidents.md)
**Snooze an incident**
**Operation ID:** `createIncidentSnooze`

Snooze an incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The incident that was successfully snoozed. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

