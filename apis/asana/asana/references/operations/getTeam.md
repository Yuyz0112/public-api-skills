# GET /teams/{team_gid}

**Resource:** [Teams](../resources/Teams.md)
**Get a team**
**Operation ID:** `getTeam`

<b>Required scope: </b><code>teams:read</code>

Returns the full record for a single team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the record for a single team. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: teams:read
