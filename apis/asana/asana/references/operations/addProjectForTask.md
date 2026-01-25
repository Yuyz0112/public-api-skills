# POST /tasks/{task_gid}/addProject

**Resource:** [Tasks](../resources/Tasks.md)
**Add a project to a task**
**Operation ID:** `addProjectForTask`

<b>Required scope: </b><code>tasks:write</code>

Adds the task to the specified project, in the optional location
specified. If no location arguments are given, the task will be added to
the end of the project.

`addProject` can also be used to reorder a task within a project or
section that already contains it.

**Positioning the task:**
- Use `insert_before` or `insert_after` with a task ID to position relative to another task
- Use `section` alone to add the task to the end of a section
- Use `section` with `insert_after: null` to add to the **beginning** of a section
- Use `section` with `insert_before: null` to add to the **end** of a section
- Use `section` with `insert_before` or `insert_after` (non-null) to position relative to a task within that section. The anchor task must be in the specified section.

At most one of `insert_before` or `insert_after` should be specified (both cannot be used together).

A task can have at most 20 projects multi-homed to it.

Returns an empty data block.

## Request Body

The project to add the task to.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the specified project to the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write
