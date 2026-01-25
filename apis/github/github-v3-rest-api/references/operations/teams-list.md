# GET /orgs/{org}/teams

**Resource:** [teams](../resources/teams.md)
**List teams**
**Operation ID:** `teams/list`

Lists all teams in an organization that are visible to the authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |

**Success Response Schema:**

Array of [team](../schemas/team/team.md)

