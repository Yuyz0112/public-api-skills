# Project statuses

*Deprecated: new integrations should prefer using [status updates](/reference/status-updates)*

A project status is an update on the progress of a particular project,
and is sent out to all project followers when created. These updates
include both text describing the update and a color code intended to
represent the overall state of the project: "green" for projects that
are on track, "yellow" for projects at risk, "red" for projects that
are behind, and "blue" for projects on hold.

Project statuses can be created and deleted, but not modified.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/project_statuses/{project_status_gid}` | Get a project status | [View](../operations/getProjectStatus.md) |
| DELETE | `/project_statuses/{project_status_gid}` | Delete a project status | [View](../operations/deleteProjectStatus.md) |
| GET | `/projects/{project_gid}/project_statuses` | Get statuses from a project | [View](../operations/getProjectStatusesForProject.md) |
| POST | `/projects/{project_gid}/project_statuses` | Create a project status | [View](../operations/createProjectStatusForProject.md) |
