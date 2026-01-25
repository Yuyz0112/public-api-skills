# POST /teams/{team_gid}/removeUser

**Resource:** [Teams](../resources/Teams.md)
**Remove a user from a team**
**Operation ID:** `removeUserForTeam`

The user making this call must be a member of the team in order to remove themselves or others.

## Request Body

The user to remove from the team.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns an empty data record |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
