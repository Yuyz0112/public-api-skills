# GET /orgs/{org}/teams/{team_slug}/memberships/{username}

**Resource:** [teams](../resources/teams.md)
**Get team membership for a user**
**Operation ID:** `teams/get-membership-for-user-in-org`

Team members will include the members of child teams.

To get a user's membership with a team, the team must be visible to the authenticated user.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/{org_id}/team/{team_id}/memberships/{username}`.

> [!NOTE]
> The response contains the `state` of the membership and the member's `role`.

The `role` for organization owners is set to `maintainer`. For more information about `maintainer` roles, see [Create a team](https://docs.github.com/rest/teams/teams#create-a-team).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | if user has no team membership |

**Success Response Schema:**

[team-membership](../schemas/team-membership/team-membership.md)

