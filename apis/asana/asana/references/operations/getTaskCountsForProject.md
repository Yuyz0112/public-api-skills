# GET /projects/{project_gid}/task_counts

**Resource:** [Projects](../resources/Projects.md)
**Get task count of a project**
**Operation ID:** `getTaskCountsForProject`

<b>Required scope: </b><code>projects:read</code>

<table>
  <tr>
    <th>Field</th>
    <th>Required Scope</th>
  </tr>
  <tr>
    <td><code>custom_field_settings</code></td>
    <td><code>custom_fields:read</code></td>
  </tr>
  <tr>
    <td><code>team</code></td>
    <td><code>teams:read</code></td>
  </tr>
</table>

Get an object that holds task count fields. **All fields are excluded by default**. You must [opt in](/docs/inputoutput-options) using `opt_fields` to get any information from this endpoint.

This endpoint has an additional [rate limit](/docs/rate-limits) and each field counts especially high against our [cost limits](/docs/rate-limits#cost-limits).

Milestones are just tasks, so they are included in the `num_tasks`, `num_incomplete_tasks`, and `num_completed_tasks` counts.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested project's task counts. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:read
