# GET /repos/{owner}/{repo}/branches/{branch}/protection/restrictions

**Resource:** [repos](../resources/repos.md)
**Get access restrictions**
**Operation ID:** `repos/get-access-restrictions`

Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products) in the GitHub Help documentation.

Lists who has access to this protected branch.

> [!NOTE]
> Users, apps, and teams `restrictions` are only available for organization-owned repositories.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[branch-restriction-policy](../schemas/branch-restriction-policy/branch-restriction-policy.md)

