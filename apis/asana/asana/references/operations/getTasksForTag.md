# GET /tags/{tag_gid}/tasks

**Resource:** [Tasks](../resources/Tasks.md)
**Get tasks from a tag**
**Operation ID:** `getTasksForTag`

<b>Required scope: </b><code>tasks:read</code>

Returns the compact task records for all tasks with the given tag. Tasks can have more than one tag at a time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the tasks associated with the specified tag. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read
