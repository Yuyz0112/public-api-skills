# GET /orgs/{org}/teams/{team_slug}/repos

**Resource:** [teams](../resources/teams.md)
**List team repositories**
**Operation ID:** `teams/list-repos-in-org`

Lists a team's repositories visible to the authenticated user.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/{org_id}/team/{team_id}/repos`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

