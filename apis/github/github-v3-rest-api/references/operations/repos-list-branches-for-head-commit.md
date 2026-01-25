# GET /repos/{owner}/{repo}/commits/{commit_sha}/branches-where-head

**Resource:** [repos](../resources/repos.md)
**List branches for HEAD commit**
**Operation ID:** `repos/list-branches-for-head-commit`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Returns all branches where the given commit SHA is the HEAD, or latest commit for the branch.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 409 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [branch-short](../schemas/branch-short/branch-short.md)

