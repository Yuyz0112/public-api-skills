# GET /teams/{team_gid}/team_memberships

**Resource:** [Team memberships](../resources/Team-memberships.md)
**Get memberships from a team**
**Operation ID:** `getTeamMembershipsForTeam`

<b>Required scope: </b><code>team_memberships:read</code>

Returns the compact team memberships for the team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested team's memberships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: team_memberships:read
