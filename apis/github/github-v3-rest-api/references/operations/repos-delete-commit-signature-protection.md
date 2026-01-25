# DELETE /repos/{owner}/{repo}/branches/{branch}/protection/required_signatures

**Resource:** [repos](../resources/repos.md)
**Delete commit signature protection**
**Operation ID:** `repos/delete-commit-signature-protection`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

When authenticated with admin or owner permissions to the repository, you can use this endpoint to disable required signed commits on a branch. You must enable branch protection to require signed commits.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

