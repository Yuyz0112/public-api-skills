# GET /repos/{owner}/{repo}/automated-security-fixes

**Resource:** [repos](../resources/repos.md)
**Check if Dependabot security updates are enabled for a repository**
**Operation ID:** `repos/check-automated-security-fixes`

Shows whether Dependabot security updates are enabled, disabled or paused for a repository. The authenticated user must have admin read access to the repository. For more information, see "[Configuring Dependabot security updates](https://docs.github.com/articles/configuring-automated-security-fixes)".

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response if Dependabot is enabled |
| 404 | Not Found if Dependabot is not enabled for the repository |

**Success Response Schema:**

[check-automated-security-fixes](../schemas/check-automated-security-fixes/check-automated-security-fixes.md)

