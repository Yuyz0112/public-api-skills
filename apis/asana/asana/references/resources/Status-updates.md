# Status updates

A status update is an update on the progress of a particular object,
and is sent out to all followers when created. These updates
include both text describing the update and a `status_type` intended to
represent the overall state of the project. These include: `on_track` for projects that
are on track, `at_risk` for projects at risk, `off_track` for projects that
are behind, and `on_hold` for projects on hold.

Status updates can be created and deleted, but not modified.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/status_updates/{status_update_gid}` | Get a status update | [View](../operations/getStatus.md) |
| DELETE | `/status_updates/{status_update_gid}` | Delete a status update | [View](../operations/deleteStatus.md) |
| GET | `/status_updates` | Get status updates from an object | [View](../operations/getStatusesForObject.md) |
| POST | `/status_updates` | Create a status update | [View](../operations/createStatusForObject.md) |
