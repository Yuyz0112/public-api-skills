# DELETE /orgs/{org}/teams/{team_slug}

**Resource:** [teams](../resources/teams.md)
**Delete a team**
**Operation ID:** `teams/delete-in-org`

To delete a team, the authenticated user must be an organization owner or team maintainer.

If you are an organization owner, deleting a parent team will delete all of its child teams as well.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `DELETE /organizations/{org_id}/team/{team_id}`.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

