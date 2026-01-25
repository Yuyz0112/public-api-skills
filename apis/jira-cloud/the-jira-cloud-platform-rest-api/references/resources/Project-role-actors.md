# Project role actors

This resource represents the users assigned to [project roles](#api-group-Issue-comments). Use it to get, add, and remove default users from project roles. Also use it to add and remove users from a project role associated with a project.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| PUT | `/rest/api/3/project/{projectIdOrKey}/role/{id}` | Set actors for project role | [View](../operations/setActors.md) |
| POST | `/rest/api/3/project/{projectIdOrKey}/role/{id}` | Add actors to project role | [View](../operations/addActorUsers.md) |
| DELETE | `/rest/api/3/project/{projectIdOrKey}/role/{id}` | Delete actors from project role | [View](../operations/deleteActor.md) |
| GET | `/rest/api/3/role/{id}/actors` | Get default actors for project role | [View](../operations/getProjectRoleActorsForRole.md) |
| POST | `/rest/api/3/role/{id}/actors` | Add default actors to project role | [View](../operations/addProjectRoleActorsToRole.md) |
| DELETE | `/rest/api/3/role/{id}/actors` | Delete default actors from project role | [View](../operations/deleteProjectRoleActorsFromRole.md) |
