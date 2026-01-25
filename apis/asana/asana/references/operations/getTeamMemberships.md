# GET /team_memberships

**Resource:** [Team memberships](../resources/Team-memberships.md)
**Get team memberships**
**Operation ID:** `getTeamMemberships`

<b>Required scope: </b><code>team_memberships:read</code>

Returns compact team membership records.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `team` | query | string | No | Globally unique identifier for the team. |
| `user` | query | string | No | A string identifying a user. This can either be the string "me", an email, or the gid of a user. This parameter must be used with the workspace parameter. |
| `workspace` | query | string | No | Globally unique identifier for the workspace. This parameter must be used with the user parameter. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested team memberships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: team_memberships:read
