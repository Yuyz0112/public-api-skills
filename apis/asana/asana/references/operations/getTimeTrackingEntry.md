# GET /time_tracking_entries/{time_tracking_entry_gid}

**Resource:** [Time tracking entries](../resources/Time-tracking-entries.md)
**Get a time tracking entry**
**Operation ID:** `getTimeTrackingEntry`

<b>Required scope: </b><code>time_tracking_entries:read</code>

Returns the complete time tracking entry record for a single time tracking entry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested time tracking entry. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: time_tracking_entries:read
