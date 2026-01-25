# GET /user/teams

**Resource:** [teams](../resources/teams.md)
**List teams for the authenticated user**
**Operation ID:** `teams/list-for-authenticated-user`

List all of the teams across all of the organizations to which the authenticated
user belongs.

OAuth app tokens and personal access tokens (classic) need the `user`, `repo`, or `read:org` scope to use this endpoint.

When using a fine-grained personal access token, the resource owner of the token must be a single organization, and the response will only include the teams from that organization.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [team-full](../schemas/team-full/team-full.md)

