# GET /repos/{owner}/{repo}/commits/{ref}/check-suites

**Resource:** [checks](../resources/checks.md)
**List check suites for a Git reference**
**Operation ID:** `checks/list-suites-for-ref`

Lists check suites for a commit `ref`. The `ref` can be a SHA, branch name, or a tag name.

> [!NOTE]
> The endpoints to manage checks only look for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array and a `null` value for `head_branch`.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint on a private repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | query | integer | No | Filters check suites by GitHub App `id`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

