# PUT /repos/{owner}/{repo}/branches/{branch}/protection

**Resource:** [repos](../resources/repos.md)
**Update branch protection**
**Operation ID:** `repos/update-branch-protection`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Protecting a branch requires admin or owner permissions to the repository.

> [!NOTE]
> Passing new arrays of `users` and `teams` replaces their previous values.

> [!NOTE]
> The list of users, apps, and teams in total is limited to 100 items.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[protected-branch](../schemas/protected-branch/protected-branch.md)

