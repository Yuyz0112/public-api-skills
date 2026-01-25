# GET /log_entries

**Resource:** [Log Entries](../resources/Log-Entries.md)
**List log entries**
**Operation ID:** `listLogEntries`

List all of the incident log entries across the entire account.

A log of all the events that happen to an Incident, and these are exposed as Log Entries.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#log-entries)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of log entries. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

