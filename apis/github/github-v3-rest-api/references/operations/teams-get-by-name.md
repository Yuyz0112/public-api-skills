# GET /orgs/{org}/teams/{team_slug}

**Resource:** [teams](../resources/teams.md)
**Get a team by name**
**Operation ID:** `teams/get-by-name`

Gets a team using the team's `slug`. To create the `slug`, GitHub replaces special characters in the `name` string, changes all words to lowercase, and replaces spaces with a `-` separator. For example, `"My TEam Näme"` would become `my-team-name`.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/{org_id}/team/{team_id}`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[team-full](../schemas/team-full/team-full.md)

