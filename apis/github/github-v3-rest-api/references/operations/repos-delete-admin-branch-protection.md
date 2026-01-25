# DELETE /repos/{owner}/{repo}/branches/{branch}/protection/enforce_admins

**Resource:** [repos](../resources/repos.md)
**Delete admin branch protection**
**Operation ID:** `repos/delete-admin-branch-protection`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Removing admin enforcement requires admin or owner permissions to the repository and branch protection to be enabled.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

