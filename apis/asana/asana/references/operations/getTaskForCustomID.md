# GET /workspaces/{workspace_gid}/tasks/custom_id/{custom_id}

**Resource:** [Tasks](../resources/Tasks.md)
**Get a task for a given custom ID**
**Operation ID:** `getTaskForCustomID`

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

Returns a task given a custom ID shortcode.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved task for given custom ID. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read
