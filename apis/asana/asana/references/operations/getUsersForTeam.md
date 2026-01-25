# GET /teams/{team_gid}/users

**Resource:** [Users](../resources/Users.md)
**Get users in a team**
**Operation ID:** `getUsersForTeam`

<b>Required scope: </b><code>users:read</code>

Returns the compact records for all users that are members of the team.
Results are sorted alphabetically and limited to 2000. For more results use the `/users` endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the user records for all the members of the team, including guests and limited access users. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: users:read
