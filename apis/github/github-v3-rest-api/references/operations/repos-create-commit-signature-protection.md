# POST /repos/{owner}/{repo}/branches/{branch}/protection/required_signatures

**Resource:** [repos](../resources/repos.md)
**Create commit signature protection**
**Operation ID:** `repos/create-commit-signature-protection`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

When authenticated with admin or owner permissions to the repository, you can use this endpoint to require signed commits on a branch. You must enable branch protection to require signed commits.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[protected-branch-admin-enforced](../schemas/protected-branch-admin-enforced/protected-branch-admin-enforced.md)

