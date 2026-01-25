# PATCH /repos/{owner}/{repo}/branches/{branch}/protection/required_pull_request_reviews

**Resource:** [repos](../resources/repos.md)
**Update pull request review protection**
**Operation ID:** `repos/update-pull-request-review-protection`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Updating pull request review enforcement requires admin or owner permissions to the repository and branch protection to be enabled.

> [!NOTE]
> Passing new arrays of `users` and `teams` replaces their previous values.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

[protected-branch-pull-request-review](../schemas/protected-branch-pull-request-review/protected-branch-pull-request-review.md)

