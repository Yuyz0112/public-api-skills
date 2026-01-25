# Workspaces

A *workspace* is the highest-level organizational unit in Asana. All projects and tasks have an associated workspace.

An *organization* is a special kind of workspace that represents a company. In an organization, you can group your projects into teams. You can read more about how organizations work on the Asana Guide. To tell if your workspace is an organization or not, check its `is_organization` property.

Over time, we intend to migrate most workspaces into organizations and to release more organization-specific functionality. We may eventually deprecate using workspace-based APIs for organizations. Currently, and until after some reasonable grace period following any further announcements, you can still reference organizations in any `workspace` parameter.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/workspaces` | Get multiple workspaces | [View](../operations/getWorkspaces.md) |
| GET | `/workspaces/{workspace_gid}` | Get a workspace | [View](../operations/getWorkspace.md) |
| PUT | `/workspaces/{workspace_gid}` | Update a workspace | [View](../operations/updateWorkspace.md) |
| POST | `/workspaces/{workspace_gid}/addUser` | Add a user to a workspace or organization | [View](../operations/addUserForWorkspace.md) |
| POST | `/workspaces/{workspace_gid}/removeUser` | Remove a user from a workspace or organization | [View](../operations/removeUserForWorkspace.md) |
| GET | `/workspaces/{workspace_gid}/events` | Get workspace events | [View](../operations/getWorkspaceEvents.md) |
