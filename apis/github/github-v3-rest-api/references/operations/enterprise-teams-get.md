# GET /enterprises/{enterprise}/teams/{team_slug}

**Resource:** [enterprise-teams](../resources/enterprise-teams.md)
**Get an enterprise team**
**Operation ID:** `enterprise-teams/get`

Gets a team using the team's slug. To create the slug, GitHub replaces special characters in the name string, changes all words to lowercase, and replaces spaces with a `-` separator and adds the "ent:" prefix. For example, "My TEam Näme" would become `ent:my-team-name`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |

**Success Response Schema:**

[enterprise-team](../schemas/enterprise-team/enterprise-team.md)

