# POST /repos/{owner}/{repo}/check-suites

**Resource:** [checks](../resources/checks.md)
**Create a check suite**
**Operation ID:** `checks/create-suite`

Creates a check suite manually. By default, check suites are automatically created when you create a [check run](https://docs.github.com/rest/checks/runs). You only need to use this endpoint for manually creating check suites when you've disabled automatic creation using "[Update repository preferences for check suites](https://docs.github.com/rest/checks/suites#update-repository-preferences-for-check-suites)".

> [!NOTE]
> The Checks API only looks for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array and a `null` value for `head_branch`.

OAuth apps and personal access tokens (classic) cannot use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response when the suite already exists |
| 201 | Response when the suite was created |

**Success Response Schema:**

[check-suite](../schemas/check-suite/check-suite.md)

