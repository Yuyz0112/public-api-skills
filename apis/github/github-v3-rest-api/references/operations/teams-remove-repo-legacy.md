# DELETE /teams/{team_id}/repos/{owner}/{repo}

**Resource:** [teams](../resources/teams.md)
**Remove a repository from a team (Legacy)**
**Operation ID:** `teams/remove-repo-legacy`
⚠️ **Deprecated**

> [!WARNING]
> **Endpoint closing down notice:** This endpoint route is closing down and will be removed from the Teams API. We recommend migrating your existing code to use the new [Remove a repository from a team](https://docs.github.com/rest/teams/teams#remove-a-repository-from-a-team) endpoint.

If the authenticated user is an organization owner or a team maintainer, they can remove any repositories from the team. To remove a repository from a team as an organization member, the authenticated user must have admin access to the repository and must be able to see the team. NOTE: This does not delete the repository, it just removes it from the team.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

