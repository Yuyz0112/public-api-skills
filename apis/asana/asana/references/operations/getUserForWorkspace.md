# GET /workspaces/{workspace_gid}/users/{user_gid}

**Resource:** [Users](../resources/Users.md)
**Get a user in a workspace or organization**
**Operation ID:** `getUserForWorkspace`

<b>Required scope: </b><code>users:read</code>

Returns the full user record for the single user with the provided ID in the specified workspace or organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the user specified. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: users:read
