# GET /time_tracking_entries

**Resource:** [Time tracking entries](../resources/Time-tracking-entries.md)
**Get multiple time tracking entries**
**Operation ID:** `getTimeTrackingEntries`

<b>Required scope: </b><code>time_tracking_entries:read</code>

Returns a list of time tracking entries filtered to a task, attributed project, portfolio or user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `task` | query | string | No | Globally unique identifier for the task to filter time tracking entries by. |
| `attributable_to` | query | string | No | Globally unique identifier for the project the time tracking entries are attributed to. |
| `portfolio` | query | string | No | Globally unique identifier for the portfolio to filter time tracking entries by. |
| `user` | query | string | No | Globally unique identifier for the user to filter time tracking entries by. |
| `workspace` | query | string | No | Globally unique identifier for the workspace. At least one of `entered_on_start_date` or `entered_on_end_date` must be provided when filtering by workspace. |
| `entered_on_start_date` | query | string (date) | No | The start date for filtering time tracking entries by when they were entered. |
| `entered_on_end_date` | query | string (date) | No | The end date for filtering time tracking entries by when they were entered. |
| `timesheet_approval_status` | query | string | No | Globally unique identifier for the timesheet approval status to filter time tracking entries by. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested time tracking entries. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: time_tracking_entries:read
