# PATCH /repos/{owner}/{repo}/check-runs/{check_run_id}

**Resource:** [checks](../resources/checks.md)
**Update a check run**
**Operation ID:** `checks/update`

Updates a check run for a specific commit in a repository.

> [!NOTE]
> The endpoints to manage checks only look for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array.

OAuth apps and personal access tokens (classic) cannot use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[check-run](../schemas/check-run/check-run.md)

