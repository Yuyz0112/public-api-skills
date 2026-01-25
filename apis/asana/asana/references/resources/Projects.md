# Projects

A project represents a prioritized list of tasks in Asana or a board with columns of tasks represented as cards. A project exists in a single workspace or organization and is accessible to a subset of users in that workspace or organization, depending on its permissions.

Projects in organizations are shared with a single team. Currently, the team of a project cannot be changed via the API. Non-organization workspaces do not have teams and so you should not specify the team of project in a regular workspace.

Followers of a project are a subset of the members of that project. Followers of a project will receive all updates including tasks created, added and removed from that project. Members of the project have access to and will receive status updates of the project. Adding followers to a project will add them as members if they are not already, removing followers from a project will not affect membership.

**Note:** You can use certain project endpoints to operate on [user task lists](/reference/user-task-lists) ([My Tasks](https://asana.com/guide/help/fundamentals/my-tasks)) by substituting the `{project_gid}` with the `{user_task_list_gid}`. For example, you can perform operations on the custom fields of a user task list by using the following projects endpoints: [Add a custom field to a project](/reference/addcustomfieldsettingforproject), [Remove a custom field from a project](/reference/removecustomfieldsettingforproject) and [Get a project's custom fields](/reference/getcustomfieldsettingsforproject)

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/projects` | Get multiple projects | [View](../operations/getProjects.md) |
| POST | `/projects` | Create a project | [View](../operations/createProject.md) |
| GET | `/projects/{project_gid}` | Get a project | [View](../operations/getProject.md) |
| PUT | `/projects/{project_gid}` | Update a project | [View](../operations/updateProject.md) |
| DELETE | `/projects/{project_gid}` | Delete a project | [View](../operations/deleteProject.md) |
| POST | `/projects/{project_gid}/duplicate` | Duplicate a project | [View](../operations/duplicateProject.md) |
| GET | `/tasks/{task_gid}/projects` | Get projects a task is in | [View](../operations/getProjectsForTask.md) |
| GET | `/teams/{team_gid}/projects` | Get a team's projects | [View](../operations/getProjectsForTeam.md) |
| POST | `/teams/{team_gid}/projects` | Create a project in a team | [View](../operations/createProjectForTeam.md) |
| GET | `/workspaces/{workspace_gid}/projects` | Get all projects in a workspace | [View](../operations/getProjectsForWorkspace.md) |
| POST | `/workspaces/{workspace_gid}/projects` | Create a project in a workspace | [View](../operations/createProjectForWorkspace.md) |
| POST | `/projects/{project_gid}/addCustomFieldSetting` | Add a custom field to a project | [View](../operations/addCustomFieldSettingForProject.md) |
| POST | `/projects/{project_gid}/removeCustomFieldSetting` | Remove a custom field from a project | [View](../operations/removeCustomFieldSettingForProject.md) |
| GET | `/projects/{project_gid}/task_counts` | Get task count of a project | [View](../operations/getTaskCountsForProject.md) |
| POST | `/projects/{project_gid}/addMembers` | Add users to a project | [View](../operations/addMembersForProject.md) |
| POST | `/projects/{project_gid}/removeMembers` | Remove users from a project | [View](../operations/removeMembersForProject.md) |
| POST | `/projects/{project_gid}/addFollowers` | Add followers to a project | [View](../operations/addFollowersForProject.md) |
| POST | `/projects/{project_gid}/removeFollowers` | Remove followers from a project | [View](../operations/removeFollowersForProject.md) |
| POST | `/projects/{project_gid}/saveAsTemplate` | Create a project template from a project | [View](../operations/projectSaveAsTemplate.md) |
