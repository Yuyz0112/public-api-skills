# GET /repos/{owner}/{repo}/teams

**Resource:** [repos](../resources/repos.md)
**List repository teams**
**Operation ID:** `repos/list-teams`

Lists the teams that have access to the specified repository and that are also visible to the authenticated user.

For a public repository, a team is listed only if that team added the public repository explicitly.

OAuth app tokens and personal access tokens (classic) need the `public_repo` or `repo` scope to use this endpoint with a public repository, and `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [team](../schemas/team/team.md)

