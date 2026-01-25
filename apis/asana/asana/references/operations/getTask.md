# GET /tasks/{task_gid}

**Resource:** [Tasks](../resources/Tasks.md)
**Get a task**
**Operation ID:** `getTask`

<b>Required scope: </b><code>tasks:read</code>

<table>
  <tr>
    <th>Field</th>
    <th>Required Scope</th>
  </tr>
  <tr>
    <td><code>memberships</code></td>
    <td><code>projects:read</code>, <code>project_sections:read</code></td>
  </tr>
  <tr>
    <td><code>actual_time_minutes</code></td>
    <td><code>time_tracking_entries:read</code></td>
  </tr>
</table>

Returns the complete task record for a single task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read
