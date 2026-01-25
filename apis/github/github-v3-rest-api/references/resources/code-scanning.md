# code-scanning

Retrieve code scanning alerts from a repository.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/code-scanning/alerts` | List code scanning alerts for an organization | [View](../operations/code-scanning-list-alerts-for-org.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/alerts` | List code scanning alerts for a repository | [View](../operations/code-scanning-list-alerts-for-repo.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/alerts/{alert_number}` | Get a code scanning alert | [View](../operations/code-scanning-get-alert.md) |
| PATCH | `/repos/{owner}/{repo}/code-scanning/alerts/{alert_number}` | Update a code scanning alert | [View](../operations/code-scanning-update-alert.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/autofix` | Get the status of an autofix for a code scanning alert | [View](../operations/code-scanning-get-autofix.md) |
| POST | `/repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/autofix` | Create an autofix for a code scanning alert | [View](../operations/code-scanning-create-autofix.md) |
| POST | `/repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/autofix/commits` | Commit an autofix for a code scanning alert | [View](../operations/code-scanning-commit-autofix.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/instances` | List instances of a code scanning alert | [View](../operations/code-scanning-list-alert-instances.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/analyses` | List code scanning analyses for a repository | [View](../operations/code-scanning-list-recent-analyses.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/analyses/{analysis_id}` | Get a code scanning analysis for a repository | [View](../operations/code-scanning-get-analysis.md) |
| DELETE | `/repos/{owner}/{repo}/code-scanning/analyses/{analysis_id}` | Delete a code scanning analysis from a repository | [View](../operations/code-scanning-delete-analysis.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/codeql/databases` | List CodeQL databases for a repository | [View](../operations/code-scanning-list-codeql-databases.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/codeql/databases/{language}` | Get a CodeQL database for a repository | [View](../operations/code-scanning-get-codeql-database.md) |
| DELETE | `/repos/{owner}/{repo}/code-scanning/codeql/databases/{language}` | Delete a CodeQL database | [View](../operations/code-scanning-delete-codeql-database.md) |
| POST | `/repos/{owner}/{repo}/code-scanning/codeql/variant-analyses` | Create a CodeQL variant analysis | [View](../operations/code-scanning-create-variant-analysis.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/codeql/variant-analyses/{codeql_variant_analysis_id}` | Get the summary of a CodeQL variant analysis | [View](../operations/code-scanning-get-variant-analysis.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/codeql/variant-analyses/{codeql_variant_analysis_id}/repos/{repo_owner}/{repo_name}` | Get the analysis status of a repository in a CodeQL variant analysis | [View](../operations/code-scanning-get-variant-analysis-repo-task.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/default-setup` | Get a code scanning default setup configuration | [View](../operations/code-scanning-get-default-setup.md) |
| PATCH | `/repos/{owner}/{repo}/code-scanning/default-setup` | Update a code scanning default setup configuration | [View](../operations/code-scanning-update-default-setup.md) |
| POST | `/repos/{owner}/{repo}/code-scanning/sarifs` | Upload an analysis as SARIF data | [View](../operations/code-scanning-upload-sarif.md) |
| GET | `/repos/{owner}/{repo}/code-scanning/sarifs/{sarif_id}` | Get information about a SARIF upload | [View](../operations/code-scanning-get-sarif.md) |
