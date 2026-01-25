# GET /teams/{team_id}/members/{username}

**Resource:** [teams](../resources/teams.md)
**Get team member (Legacy)**
**Operation ID:** `teams/get-member-legacy`
⚠️ **Deprecated**

The "Get team member" endpoint (described below) is closing down.

We recommend using the [Get team membership for a user](https://docs.github.com/rest/teams/members#get-team-membership-for-a-user) endpoint instead. It allows you to get both active and pending memberships.

To list members in a team, the team must be visible to the authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 204 | if user is a member |
| 404 | if user is not a member |

