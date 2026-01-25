# GET /tasks/{task_gid}/projects

**Resource:** [Projects](../resources/Projects.md)
**Get projects a task is in**
**Operation ID:** `getProjectsForTask`

<b>Required scope: </b><code>projects:read</code>

Returns a compact representation of all of the projects the task is in.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the projects for the given task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:read
