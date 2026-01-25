# checks

Rich interactions with checks run by your integrations.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/repos/{owner}/{repo}/check-runs` | Create a check run | [View](../operations/checks-create.md) |
| GET | `/repos/{owner}/{repo}/check-runs/{check_run_id}` | Get a check run | [View](../operations/checks-get.md) |
| PATCH | `/repos/{owner}/{repo}/check-runs/{check_run_id}` | Update a check run | [View](../operations/checks-update.md) |
| GET | `/repos/{owner}/{repo}/check-runs/{check_run_id}/annotations` | List check run annotations | [View](../operations/checks-list-annotations.md) |
| POST | `/repos/{owner}/{repo}/check-runs/{check_run_id}/rerequest` | Rerequest a check run | [View](../operations/checks-rerequest-run.md) |
| POST | `/repos/{owner}/{repo}/check-suites` | Create a check suite | [View](../operations/checks-create-suite.md) |
| PATCH | `/repos/{owner}/{repo}/check-suites/preferences` | Update repository preferences for check suites | [View](../operations/checks-set-suites-preferences.md) |
| GET | `/repos/{owner}/{repo}/check-suites/{check_suite_id}` | Get a check suite | [View](../operations/checks-get-suite.md) |
| GET | `/repos/{owner}/{repo}/check-suites/{check_suite_id}/check-runs` | List check runs in a check suite | [View](../operations/checks-list-for-suite.md) |
| POST | `/repos/{owner}/{repo}/check-suites/{check_suite_id}/rerequest` | Rerequest a check suite | [View](../operations/checks-rerequest-suite.md) |
| GET | `/repos/{owner}/{repo}/commits/{ref}/check-runs` | List check runs for a Git reference | [View](../operations/checks-list-for-ref.md) |
| GET | `/repos/{owner}/{repo}/commits/{ref}/check-suites` | List check suites for a Git reference | [View](../operations/checks-list-suites-for-ref.md) |
