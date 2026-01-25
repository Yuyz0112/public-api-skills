# Time tracking entries

Asana's native time tracking feature allows you to estimate the time needed to complete a task, as well as record the actual time spent.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/tasks/{task_gid}/time_tracking_entries` | Get time tracking entries for a task | [View](../operations/getTimeTrackingEntriesForTask.md) |
| POST | `/tasks/{task_gid}/time_tracking_entries` | Create a time tracking entry | [View](../operations/createTimeTrackingEntry.md) |
| GET | `/time_tracking_entries/{time_tracking_entry_gid}` | Get a time tracking entry | [View](../operations/getTimeTrackingEntry.md) |
| PUT | `/time_tracking_entries/{time_tracking_entry_gid}` | Update a time tracking entry | [View](../operations/updateTimeTrackingEntry.md) |
| DELETE | `/time_tracking_entries/{time_tracking_entry_gid}` | Delete a time tracking entry | [View](../operations/deleteTimeTrackingEntry.md) |
| GET | `/time_tracking_entries` | Get multiple time tracking entries | [View](../operations/getTimeTrackingEntries.md) |
