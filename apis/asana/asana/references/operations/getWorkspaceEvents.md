# GET /workspaces/{workspace_gid}/events

**Resource:** [Workspaces](../resources/Workspaces.md)
**Get workspace events**
**Operation ID:** `getWorkspaceEvents`

Returns the full record for all events that have occurred since the sync token was created.
The response is a list of events and the schema of each event is as described [here](/reference/events).
Asana limits a single sync token to 1000 events. If more than 1000 events exist for a given domain, `has_more: true` will be returned in the response, indicating that there are more events to pull.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved events. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
