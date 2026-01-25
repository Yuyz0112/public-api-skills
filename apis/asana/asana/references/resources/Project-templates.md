# Project templates

A project template is an object that allows new projects to be created
with a predefined setup, which may include tasks, sections, rules, etc.
It simplifies the process of running a workflow that involves a similar
set of work every time.


Project templates in organizations are shared with a single team. Currently, the
team of a project template cannot be changed via the API.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/project_templates/{project_template_gid}` | Get a project template | [View](../operations/getProjectTemplate.md) |
| DELETE | `/project_templates/{project_template_gid}` | Delete a project template | [View](../operations/deleteProjectTemplate.md) |
| GET | `/project_templates` | Get multiple project templates | [View](../operations/getProjectTemplates.md) |
| GET | `/teams/{team_gid}/project_templates` | Get a team's project templates | [View](../operations/getProjectTemplatesForTeam.md) |
| POST | `/project_templates/{project_template_gid}/instantiateProject` | Instantiate a project from a project template | [View](../operations/instantiateProject.md) |
