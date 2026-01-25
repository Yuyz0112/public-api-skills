# DELETE /orgs/{org}/teams/{team_slug}/repos/{owner}/{repo}

**Resource:** [teams](../resources/teams.md)
**Remove a repository from a team**
**Operation ID:** `teams/remove-repo-in-org`

If the authenticated user is an organization owner or a team maintainer, they can remove any repositories from the team. To remove a repository from a team as an organization member, the authenticated user must have admin access to the repository and must be able to see the team. This does not delete the repository, it just removes it from the team.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `DELETE /organizations/{org_id}/team/{team_id}/repos/{owner}/{repo}`.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

