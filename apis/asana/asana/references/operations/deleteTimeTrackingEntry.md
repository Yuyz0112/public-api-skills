# DELETE /time_tracking_entries/{time_tracking_entry_gid}

**Resource:** [Time tracking entries](../resources/Time-tracking-entries.md)
**Delete a time tracking entry**
**Operation ID:** `deleteTimeTrackingEntry`

A specific, existing time tracking entry can be deleted by making a `DELETE` request on
the URL for that time tracking entry.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified time tracking entry. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
