# GET /users/{user_gid}/workspace_memberships

**Resource:** [Workspace memberships](../resources/Workspace-memberships.md)
**Get workspace memberships for a user**
**Operation ID:** `getWorkspaceMembershipsForUser`

Returns the compact workspace membership records for the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested user's workspace memberships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
