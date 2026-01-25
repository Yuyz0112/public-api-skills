# GET /repos/{owner}/{repo}/check-suites/{check_suite_id}/check-runs

**Resource:** [checks](../resources/checks.md)
**List check runs in a check suite**
**Operation ID:** `checks/list-for-suite`

Lists check runs for a check suite using its `id`.

> [!NOTE]
> The endpoints to manage checks only look for pushes in the repository where the check suite or check run were created. Pushes to a branch in a forked repository are not detected and return an empty `pull_requests` array.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint on a private repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | enum: latest, all | No | Filters check runs by their `completed_at` timestamp. `latest` returns the most recent check runs. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

