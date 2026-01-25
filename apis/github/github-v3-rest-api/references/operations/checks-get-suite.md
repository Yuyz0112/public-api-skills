# GET /repos/{owner}/{repo}/check-suites/{check_suite_id}

**Resource:** [checks](../resources/checks.md)
**Get a check suite**
**Operation ID:** `checks/get-suite`

Gets a single check suite using its `id`.

> [!NOTE]
> The Checks API only looks for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array and a `null` value for `head_branch`.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint on a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[check-suite](../schemas/check-suite/check-suite.md)

