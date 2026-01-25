# POST /tasks/{task_gid}/subtasks

**Resource:** [Tasks](../resources/Tasks.md)
**Create a subtask**
**Operation ID:** `createSubtaskForTask`

<b>Required scope: </b><code>tasks:write</code>

Creates a new subtask and adds it to the parent task. Returns the full record for the newly created subtask.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The new subtask to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created the specified subtask. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write
