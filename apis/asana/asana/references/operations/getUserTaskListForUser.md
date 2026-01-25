# GET /users/{user_gid}/user_task_list

**Resource:** [User task lists](../resources/User-task-lists.md)
**Get a user's task list**
**Operation ID:** `getUserTaskListForUser`

<b>Required scope: </b><code>tasks:read</code>

Returns the full record for a user's task list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the user's task list. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read
