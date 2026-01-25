# Projects

This resource represents projects. Use it to get, create, update, and delete projects. Also get statuses available to a project, a project's notification schemes, and update a project's type.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/project` | Get all projects | [View](../operations/getAllProjects.md) |
| POST | `/rest/api/3/project` | Create project | [View](../operations/createProject.md) |
| GET | `/rest/api/3/project/recent` | Get recent projects | [View](../operations/getRecent.md) |
| GET | `/rest/api/3/project/search` | Get projects paginated | [View](../operations/searchProjects.md) |
| GET | `/rest/api/3/project/{projectIdOrKey}` | Get project | [View](../operations/getProject.md) |
| PUT | `/rest/api/3/project/{projectIdOrKey}` | Update project | [View](../operations/updateProject.md) |
| DELETE | `/rest/api/3/project/{projectIdOrKey}` | Delete project | [View](../operations/deleteProject.md) |
| POST | `/rest/api/3/project/{projectIdOrKey}/archive` | Archive project | [View](../operations/archiveProject.md) |
| POST | `/rest/api/3/project/{projectIdOrKey}/delete` | Delete project asynchronously | [View](../operations/deleteProjectAsynchronously.md) |
| POST | `/rest/api/3/project/{projectIdOrKey}/restore` | Restore deleted or archived project | [View](../operations/restore.md) |
| GET | `/rest/api/3/project/{projectIdOrKey}/statuses` | Get all statuses for project | [View](../operations/getAllStatuses.md) |
| GET | `/rest/api/3/project/{projectId}/hierarchy` | Get project issue type hierarchy | [View](../operations/getHierarchy.md) |
| GET | `/rest/api/3/project/{projectKeyOrId}/notificationscheme` | Get project notification scheme | [View](../operations/getNotificationSchemeForProject.md) |
