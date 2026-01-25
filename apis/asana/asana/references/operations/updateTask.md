# PUT /tasks/{task_gid}

**Resource:** [Tasks](../resources/Tasks.md)
**Update a task**
**Operation ID:** `updateTask`

<b>Required scope: </b><code>tasks:write</code>

A specific, existing task can be updated by making a PUT request on the
URL for that task. Only the fields provided in the `data` block will be
updated; any unspecified fields will remain unchanged.

When using this method, it is best to specify only those fields you wish
to change, or else you may overwrite changes made by another user since
you last retrieved the task.

Returns the complete updated task record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The task to update.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the specified task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write
