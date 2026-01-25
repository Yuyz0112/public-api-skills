# Task templates

A task template is an object that allows new tasks to be created with a predefined setup, which may include followers, dependencies, custom fields, etc. It simplifies the process of running a workflow that involves a similar set of work every time.
Task templates are contained within a single project.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/task_templates` | Get multiple task templates | [View](../operations/getTaskTemplates.md) |
| GET | `/task_templates/{task_template_gid}` | Get a task template | [View](../operations/getTaskTemplate.md) |
| DELETE | `/task_templates/{task_template_gid}` | Delete a task template | [View](../operations/deleteTaskTemplate.md) |
| POST | `/task_templates/{task_template_gid}/instantiateTask` | Instantiate a task from a task template | [View](../operations/instantiateTask.md) |
