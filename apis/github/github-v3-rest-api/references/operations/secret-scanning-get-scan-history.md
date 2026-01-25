# GET /repos/{owner}/{repo}/secret-scanning/scan-history

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**Get secret scanning scan history for a repository**
**Operation ID:** `secret-scanning/get-scan-history`

Lists the latest default incremental and backfill scans by type for a repository. Scans from Copilot Secret Scanning are not included.

> [!NOTE]
> This endpoint requires [GitHub Advanced Security](https://docs.github.com/get-started/learning-about-github/about-github-advanced-security)."

OAuth app tokens and personal access tokens (classic) need the `repo` or `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | Repository does not have GitHub Advanced Security or secret scanning enabled |
| 503 | (reference) |

**Success Response Schema:**

[secret-scanning-scan-history](../schemas/secret-scanning-scan-history/secret-scanning-scan-history.md)

