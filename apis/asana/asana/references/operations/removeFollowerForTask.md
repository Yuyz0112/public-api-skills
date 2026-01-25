# POST /tasks/{task_gid}/removeFollowers

**Resource:** [Tasks](../resources/Tasks.md)
**Remove followers from a task**
**Operation ID:** `removeFollowerForTask`

<b>Required scope: </b><code>tasks:write</code>

Removes each of the specified followers from the task if they are following. Returns the complete, updated record for the affected task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The followers to remove from the task.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the specified followers from the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write
