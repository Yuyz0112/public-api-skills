# POST /repos/{owner}/{repo}/check-runs

**Resource:** [checks](../resources/checks.md)
**Create a check run**
**Operation ID:** `checks/create`

Creates a new check run for a specific commit in a repository.

To create a check run, you must use a GitHub App. OAuth apps and authenticated users are not able to create a check suite.

In a check suite, GitHub limits the number of check runs with the same name to 1000. Once these check runs exceed 1000, GitHub will start to automatically delete older check runs.

> [!NOTE]
> The Checks API only looks for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[check-run](../schemas/check-run/check-run.md)

