# secret-scanning

Retrieve secret scanning alerts from a repository.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/secret-scanning/alerts` | List secret scanning alerts for an organization | [View](../operations/secret-scanning-list-alerts-for-org.md) |
| GET | `/orgs/{org}/secret-scanning/pattern-configurations` | List organization pattern configurations | [View](../operations/secret-scanning-list-org-pattern-configs.md) |
| PATCH | `/orgs/{org}/secret-scanning/pattern-configurations` | Update organization pattern configurations | [View](../operations/secret-scanning-update-org-pattern-configs.md) |
| GET | `/repos/{owner}/{repo}/secret-scanning/alerts` | List secret scanning alerts for a repository | [View](../operations/secret-scanning-list-alerts-for-repo.md) |
| GET | `/repos/{owner}/{repo}/secret-scanning/alerts/{alert_number}` | Get a secret scanning alert | [View](../operations/secret-scanning-get-alert.md) |
| PATCH | `/repos/{owner}/{repo}/secret-scanning/alerts/{alert_number}` | Update a secret scanning alert | [View](../operations/secret-scanning-update-alert.md) |
| GET | `/repos/{owner}/{repo}/secret-scanning/alerts/{alert_number}/locations` | List locations for a secret scanning alert | [View](../operations/secret-scanning-list-locations-for-alert.md) |
| POST | `/repos/{owner}/{repo}/secret-scanning/push-protection-bypasses` | Create a push protection bypass | [View](../operations/secret-scanning-create-push-protection-bypass.md) |
| GET | `/repos/{owner}/{repo}/secret-scanning/scan-history` | Get secret scanning scan history for a repository | [View](../operations/secret-scanning-get-scan-history.md) |
