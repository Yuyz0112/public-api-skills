# GET /projects/{project_gid}

**Resource:** [Projects](../resources/Projects.md)
**Get a project**
**Operation ID:** `getProject`

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

Returns the complete project record for a single project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:read
