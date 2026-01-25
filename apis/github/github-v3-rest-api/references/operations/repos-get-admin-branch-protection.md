# GET /repos/{owner}/{repo}/branches/{branch}/protection/enforce_admins

**Resource:** [repos](../resources/repos.md)
**Get admin branch protection**
**Operation ID:** `repos/get-admin-branch-protection`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[protected-branch-admin-enforced](../schemas/protected-branch-admin-enforced/protected-branch-admin-enforced.md)

