# Users

A user object represents an account in Asana that can be given access to various workspaces, projects, and tasks.

Like other objects in the system, users are referred to by numerical IDs. However, the special string identifier `me` can be used anywhere a user ID is accepted, to refer to the current authenticated user (e.g, `GET /users/me`).

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/users` | Get multiple users | [View](../operations/getUsers.md) |
| GET | `/users/{user_gid}` | Get a user | [View](../operations/getUser.md) |
| PUT | `/users/{user_gid}` | Update a user | [View](../operations/updateUser.md) |
| GET | `/users/{user_gid}/favorites` | Get a user's favorites | [View](../operations/getFavoritesForUser.md) |
| GET | `/teams/{team_gid}/users` | Get users in a team | [View](../operations/getUsersForTeam.md) |
| GET | `/workspaces/{workspace_gid}/users` | Get users in a workspace or organization | [View](../operations/getUsersForWorkspace.md) |
| GET | `/workspaces/{workspace_gid}/users/{user_gid}` | Get a user in a workspace or organization | [View](../operations/getUserForWorkspace.md) |
| PUT | `/workspaces/{workspace_gid}/users/{user_gid}` | Update a user in a workspace or organization | [View](../operations/updateUserForWorkspace.md) |
