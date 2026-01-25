# POST /tasks/{task_gid}/time_tracking_entries

**Resource:** [Time tracking entries](../resources/Time-tracking-entries.md)
**Create a time tracking entry**
**Operation ID:** `createTimeTrackingEntry`

Creates a time tracking entry on a given task.

Returns the record of the newly created time tracking entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Information about the time tracking entry.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created a time tracking entry for the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
