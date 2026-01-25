# GET /teams/{team_id}/repos/{owner}/{repo}

**Resource:** [teams](../resources/teams.md)
**Check team permissions for a repository (Legacy)**
**Operation ID:** `teams/check-permissions-for-repo-legacy`
⚠️ **Deprecated**

> [!WARNING]
> **Endpoint closing down notice:** This endpoint route is closing down and will be removed from the Teams API. We recommend migrating your existing code to use the new [Check team permissions for a repository](https://docs.github.com/rest/teams/teams#check-team-permissions-for-a-repository) endpoint.

> [!NOTE]
> Repositories inherited through a parent team will also be checked.

You can also get information about the specified repository, including what permissions the team grants on it, by passing the following custom [media type](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types/) via the `Accept` header:

## Responses

| Status | Description |
|--------|-------------|
| 200 | Alternative response with extra repository information |
| 204 | Response if repository is managed by this team |
| 404 | Not Found if repository is not managed by this team |

**Success Response Schema:**

[team-repository](../schemas/team-repository/team-repository.md)

