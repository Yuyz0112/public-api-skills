# Teams

A team is used to group related projects and people together within an organization. Each project in an organization is associated with a team.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/teams` | Create a team | [View](../operations/createTeam.md) |
| GET | `/teams/{team_gid}` | Get a team | [View](../operations/getTeam.md) |
| PUT | `/teams/{team_gid}` | Update a team | [View](../operations/updateTeam.md) |
| GET | `/workspaces/{workspace_gid}/teams` | Get teams in a workspace | [View](../operations/getTeamsForWorkspace.md) |
| GET | `/users/{user_gid}/teams` | Get teams for a user | [View](../operations/getTeamsForUser.md) |
| POST | `/teams/{team_gid}/addUser` | Add a user to a team | [View](../operations/addUserForTeam.md) |
| POST | `/teams/{team_gid}/removeUser` | Remove a user from a team | [View](../operations/removeUserForTeam.md) |
