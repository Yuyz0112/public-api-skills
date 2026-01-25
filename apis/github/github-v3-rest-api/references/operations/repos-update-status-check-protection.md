# PATCH /repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks

**Resource:** [repos](../resources/repos.md)
**Update status check protection**
**Operation ID:** `repos/update-status-check-protection`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Updating required status checks requires admin or owner permissions to the repository and branch protection to be enabled.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[status-check-policy](../schemas/status-check-policy/status-check-policy.md)

