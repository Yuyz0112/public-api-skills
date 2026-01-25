# POST /tasks/{task_gid}/addFollowers

**Resource:** [Tasks](../resources/Tasks.md)
**Add followers to a task**
**Operation ID:** `addFollowersForTask`

<b>Required scope: </b><code>tasks:write</code>

Adds followers to a task. Returns an empty data block.
Each task can be associated with zero or more followers in the system.
Requests to add/remove followers, if successful, will return the complete updated task record, described above.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The followers to add to the task.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the specified followers to the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write
