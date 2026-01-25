# GET /repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}/jobs

**Resource:** [actions](../resources/actions.md)
**List jobs for a workflow run attempt**
**Operation ID:** `actions/list-jobs-for-workflow-run-attempt`

Lists jobs for a specific workflow run attempt. You can use parameters to narrow the list of results. For more information
about using parameters, see [Parameters](https://docs.github.com/rest/guides/getting-started-with-the-rest-api#parameters).

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint  with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

