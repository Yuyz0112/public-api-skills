# POST /teams/{team_gid}/addUser

**Resource:** [Teams](../resources/Teams.md)
**Add a user to a team**
**Operation ID:** `addUserForTeam`

The user making this call must be a member of the team in order to add others. The user being added must exist in the same organization as the team.

Returns the complete team membership record for the newly added user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The user to add to the team.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added user to the team. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
