# GET /workspaces/{workspace_gid}/teams

**Resource:** [Teams](../resources/Teams.md)
**Get teams in a workspace**
**Operation ID:** `getTeamsForWorkspace`

<b>Required scope: </b><code>teams:read</code>

Returns the compact records for all teams in the workspace visible to the authorized user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the team records for all teams in the organization or workspace accessible to the authenticated user. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: teams:read
