# GET /tasks/{task_gid}/dependents

**Resource:** [Tasks](../resources/Tasks.md)
**Get dependents from a task**
**Operation ID:** `getDependentsForTask`

<b>Required scope: </b><code>tasks:read</code>

Returns the compact representations of all of the dependents of a task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified dependents of the task. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read
