# GET /tasks/{task_gid}/tags

**Resource:** [Tags](../resources/Tags.md)
**Get a task's tags**
**Operation ID:** `getTagsForTask`

<b>Required scope: </b><code>tags:read</code>

Get a compact representation of all of the tags the task has.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the tags for the given task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tags:read
