# GET /repos/{owner}/{repo}/check-runs/{check_run_id}

**Resource:** [checks](../resources/checks.md)
**Get a check run**
**Operation ID:** `checks/get`

Gets a single check run using its `id`.

> [!NOTE]
> The Checks API only looks for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint on a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[check-run](../schemas/check-run/check-run.md)

