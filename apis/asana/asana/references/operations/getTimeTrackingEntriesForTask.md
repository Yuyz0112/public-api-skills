# GET /tasks/{task_gid}/time_tracking_entries

**Resource:** [Time tracking entries](../resources/Time-tracking-entries.md)
**Get time tracking entries for a task**
**Operation ID:** `getTimeTrackingEntriesForTask`

<b>Required scope: </b><code>time_tracking_entries:read</code>

Returns time tracking entries for a given task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested time tracking entries. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: time_tracking_entries:read
