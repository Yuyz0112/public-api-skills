# GET /workspaces/{workspace_gid}/users

**Resource:** [Users](../resources/Users.md)
**Get users in a workspace or organization**
**Operation ID:** `getUsersForWorkspace`

<b>Required scope: </b><code>users:read</code>

Returns the compact records for all users in the specified workspace or organization.
Results are sorted alphabetically and limited to 2000. For more results use the `/users` endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Return the users in the specified workspace or org. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: users:read
