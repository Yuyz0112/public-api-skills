# Tasks

The task is the basic object around which many operations in Asana are centered. In the Asana application, multiple tasks populate the middle pane according to some view parameters, and the set of selected tasks determines the more detailed information presented in the details pane.

Sections are unique in that they will be included in the `memberships` field of task objects returned in the API when the task is within a section. They can also be used to manipulate the ordering of a task within a project.

[Queries](/reference/gettasks) return a [compact representation of each task object](/reference/tasks). To retrieve *all* fields or *specific set* of the fields, use [field selectors](/docs/inputoutput-options) to manipulate what data is included in a response.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/tasks` | Get multiple tasks | [View](../operations/getTasks.md) |
| POST | `/tasks` | Create a task | [View](../operations/createTask.md) |
| GET | `/tasks/{task_gid}` | Get a task | [View](../operations/getTask.md) |
| PUT | `/tasks/{task_gid}` | Update a task | [View](../operations/updateTask.md) |
| DELETE | `/tasks/{task_gid}` | Delete a task | [View](../operations/deleteTask.md) |
| POST | `/tasks/{task_gid}/duplicate` | Duplicate a task | [View](../operations/duplicateTask.md) |
| GET | `/projects/{project_gid}/tasks` | Get tasks from a project | [View](../operations/getTasksForProject.md) |
| GET | `/sections/{section_gid}/tasks` | Get tasks from a section | [View](../operations/getTasksForSection.md) |
| GET | `/tags/{tag_gid}/tasks` | Get tasks from a tag | [View](../operations/getTasksForTag.md) |
| GET | `/user_task_lists/{user_task_list_gid}/tasks` | Get tasks from a user task list | [View](../operations/getTasksForUserTaskList.md) |
| GET | `/tasks/{task_gid}/subtasks` | Get subtasks from a task | [View](../operations/getSubtasksForTask.md) |
| POST | `/tasks/{task_gid}/subtasks` | Create a subtask | [View](../operations/createSubtaskForTask.md) |
| POST | `/tasks/{task_gid}/setParent` | Set the parent of a task | [View](../operations/setParentForTask.md) |
| GET | `/tasks/{task_gid}/dependencies` | Get dependencies from a task | [View](../operations/getDependenciesForTask.md) |
| POST | `/tasks/{task_gid}/addDependencies` | Set dependencies for a task | [View](../operations/addDependenciesForTask.md) |
| POST | `/tasks/{task_gid}/removeDependencies` | Unlink dependencies from a task | [View](../operations/removeDependenciesForTask.md) |
| GET | `/tasks/{task_gid}/dependents` | Get dependents from a task | [View](../operations/getDependentsForTask.md) |
| POST | `/tasks/{task_gid}/addDependents` | Set dependents for a task | [View](../operations/addDependentsForTask.md) |
| POST | `/tasks/{task_gid}/removeDependents` | Unlink dependents from a task | [View](../operations/removeDependentsForTask.md) |
| POST | `/tasks/{task_gid}/addProject` | Add a project to a task | [View](../operations/addProjectForTask.md) |
| POST | `/tasks/{task_gid}/removeProject` | Remove a project from a task | [View](../operations/removeProjectForTask.md) |
| POST | `/tasks/{task_gid}/addTag` | Add a tag to a task | [View](../operations/addTagForTask.md) |
| POST | `/tasks/{task_gid}/removeTag` | Remove a tag from a task | [View](../operations/removeTagForTask.md) |
| POST | `/tasks/{task_gid}/addFollowers` | Add followers to a task | [View](../operations/addFollowersForTask.md) |
| POST | `/tasks/{task_gid}/removeFollowers` | Remove followers from a task | [View](../operations/removeFollowerForTask.md) |
| GET | `/workspaces/{workspace_gid}/tasks/custom_id/{custom_id}` | Get a task for a given custom ID | [View](../operations/getTaskForCustomID.md) |
| GET | `/workspaces/{workspace_gid}/tasks/search` | Search tasks in a workspace | [View](../operations/searchTasksForWorkspace.md) |
