# GET /incidents/{id}/log_entries

**Resource:** [Incidents](../resources/Incidents.md)
**List log entries for an incident**
**Operation ID:** `listIncidentLogEntries`

List log entries for the specified incident.

An incident represents a problem or an issue that needs to be addressed and resolved.

A Log Entry are a record of all events on your account.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of the incident's log entries. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

