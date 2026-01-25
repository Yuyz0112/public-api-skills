# GET /repos/{owner}/{repo}/branches/{branch}/protection/restrictions/teams

**Resource:** [repos](../resources/repos.md)
**Get teams with access to the protected branch**
**Operation ID:** `repos/get-teams-with-access-to-protected-branch`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Lists the teams who have push access to this branch. The list includes child teams.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [team](../schemas/team/team.md)

