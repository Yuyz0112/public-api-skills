# GET /projects

**Resource:** [Projects](../resources/Projects.md)
**Get multiple projects**
**Operation ID:** `getProjects`

<b>Required scope: </b><code>projects:read</code>

Returns the compact project records for some filtered set of projects. Use one or more of the parameters provided to filter the projects returned.
*Note: This endpoint may timeout for large domains. Try filtering by team!*
**The `team` filter is deprecated.** Please use `GET /memberships` with `{ member: team, resource_subtype: project_membership }` to find projects shared with a team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workspace` | query | string | No | The workspace or organization to filter projects on. |
| `team` | query | string | No | **Deprecated.** The team to filter projects on. Please use `GET /memberships` with `{ member: team, resource_subtype: project_membership }` instead. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved projects. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:read
