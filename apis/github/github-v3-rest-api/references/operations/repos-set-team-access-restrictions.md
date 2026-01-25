# PUT /repos/{owner}/{repo}/branches/{branch}/protection/restrictions/teams

**Resource:** [repos](../resources/repos.md)
**Set team access restrictions**
**Operation ID:** `repos/set-team-access-restrictions`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Replaces the list of teams that have push access to this branch. This removes all teams that previously had push access and grants push access to the new list of teams. Team restrictions include child teams.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

Array of [team](../schemas/team/team.md)

