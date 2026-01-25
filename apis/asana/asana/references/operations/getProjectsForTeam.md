# GET /teams/{team_gid}/projects

**Resource:** [Projects](../resources/Projects.md)
**Get a team's projects**
**Operation ID:** `getProjectsForTeam`
⚠️ **Deprecated**

<b>Required scope: </b><code>projects:read</code>

Returns the compact project records for all projects in the team.
*Deprecated: This endpoint is deprecated. Use `GET /memberships` with `member` set to the team GID and `resource_subtype` set to `project_membership` to fetch projects shared with a team.*

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested team's projects. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:read
