# GET /users/{user_gid}/team_memberships

**Resource:** [Team memberships](../resources/Team-memberships.md)
**Get memberships from a user**
**Operation ID:** `getTeamMembershipsForUser`

<b>Required scope: </b><code>team_memberships:read</code>

Returns the compact team membership records for the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workspace` | query | string | Yes | Globally unique identifier for the workspace. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested users's memberships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: team_memberships:read
