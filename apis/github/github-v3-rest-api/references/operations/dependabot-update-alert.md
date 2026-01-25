# PATCH /repos/{owner}/{repo}/dependabot/alerts/{alert_number}

**Resource:** [dependabot](../resources/dependabot.md)
**Update a Dependabot alert**
**Operation ID:** `dependabot/update-alert`

The authenticated user must have access to security alerts for the repository to use this endpoint. For more information, see "[Granting access to security alerts](https://docs.github.com/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-security-and-analysis-settings-for-your-repository#granting-access-to-security-alerts)."

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[dependabot-alert](../schemas/dependabot-alert/dependabot-alert.md)

