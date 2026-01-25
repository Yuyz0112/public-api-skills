# GET /log_entries/{id}

**Resource:** [Log Entries](../resources/Log-Entries.md)
**Get a log entry**
**Operation ID:** `getLogEntry`

Get details for a specific incident log entry. This method provides additional information you can use to get at raw event data.

A log of all the events that happen to an Incident, and these are exposed as Log Entries.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#log-entries)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A single log entry. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

