# GET /repos/{owner}/{repo}/commits/{ref}/check-runs

**Resource:** [checks](../resources/checks.md)
**List check runs for a Git reference**
**Operation ID:** `checks/list-for-ref`

Lists check runs for a commit ref. The `ref` can be a SHA, branch name, or a tag name.

> [!NOTE]
> The endpoints to manage checks only look for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array.

If there are more than 1000 check suites on a single git reference, this endpoint will limit check runs to the 1000 most recent check suites. To iterate over all possible check runs, use the [List check suites for a Git reference](https://docs.github.com/rest/reference/checks#list-check-suites-for-a-git-reference) endpoint and provide the `check_suite_id` parameter to the [List check runs in a check suite](https://docs.github.com/rest/reference/checks#list-check-runs-in-a-check-suite) endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint on a private repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | enum: latest, all | No | Filters check runs by their `completed_at` timestamp. `latest` returns the most recent check runs. |
| `app_id` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

