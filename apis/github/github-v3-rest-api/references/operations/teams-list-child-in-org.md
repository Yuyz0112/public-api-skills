# GET /orgs/{org}/teams/{team_slug}/teams

**Resource:** [teams](../resources/teams.md)
**List child teams**
**Operation ID:** `teams/list-child-in-org`

Lists the child teams of the team specified by `{team_slug}`.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/{org_id}/team/{team_id}/teams`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | if child teams exist |

**Success Response Schema:**

Array of [team](../schemas/team/team.md)

