# PUT /log_entries/{id}/channel

**Resource:** [Log Entries](../resources/Log-Entries.md)
**Update log entry channel information.**
**Operation ID:** `updateLogEntryChannel`

Update an existing incident log entry channel.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#log-entries)

Scoped OAuth requires: `incidents.write`


## Request Body

The log entry channel to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | The channel information modification was accepted. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

