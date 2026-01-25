# GET /repos/{owner}/{repo}/actions/runs/{run_id}/jobs

**Resource:** [actions](../resources/actions.md)
**List jobs for a workflow run**
**Operation ID:** `actions/list-jobs-for-workflow-run`

Lists jobs for a workflow run. You can use parameters to narrow the list of results. For more information
about using parameters, see [Parameters](https://docs.github.com/rest/guides/getting-started-with-the-rest-api#parameters).

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | enum: latest, all | No | Filters jobs by their `completed_at` timestamp. `latest` returns jobs from the most recent execution of the workflow run. `all` returns all jobs for a workflow run, including from old executions of the workflow run. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

