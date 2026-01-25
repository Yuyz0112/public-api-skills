# GET /orgs/{org}/teams/{team_slug}/repos/{owner}/{repo}

**Resource:** [teams](../resources/teams.md)
**Check team permissions for a repository**
**Operation ID:** `teams/check-permissions-for-repo-in-org`

Checks whether a team has `admin`, `push`, `maintain`, `triage`, or `pull` permission for a repository. Repositories inherited through a parent team will also be checked.

You can also get information about the specified repository, including what permissions the team grants on it, by passing the following custom [media type](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types/) via the `application/vnd.github.v3.repository+json` accept header.

If a team doesn't have permission for the repository, you will receive a `404 Not Found` response status.

If the repository is private, you must have at least `read` permission for that repository, and your token must have the `repo` or `admin:org` scope. Otherwise, you will receive a `404 Not Found` response status.

> [!NOTE]
> You can also specify a team by `org_id` and `team_id` using the route `GET /organizations/{org_id}/team/{team_id}/repos/{owner}/{repo}`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Alternative response with repository permissions |
| 204 | Response if team has permission for the repository. This is the response when the repository media type hasn't been provded in the Accept header. |
| 404 | Not Found if team does not have permission for the repository |

**Success Response Schema:**

[team-repository](../schemas/team-repository/team-repository.md)

