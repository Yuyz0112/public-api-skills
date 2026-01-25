# POST /sections/{section_gid}/addTask

**Resource:** [Sections](../resources/Sections.md)
**Add task to section**
**Operation ID:** `addTaskForSection`

<b>Required scope: </b><code>tasks:write</code>

Add a task to a specific, existing section. This will remove the task from other sections of the project.

The task will be inserted at the top of a section unless an insert_before or insert_after parameter is declared.

This does not work for separators (tasks with the resource_subtype of section).

## Request Body

The task and optionally the insert location.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write
