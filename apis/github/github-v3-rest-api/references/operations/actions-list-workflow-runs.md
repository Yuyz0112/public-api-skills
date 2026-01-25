# GET /repos/{owner}/{repo}/actions/workflows/{workflow_id}/runs

**Resource:** [actions](../resources/actions.md)
**List workflow runs for a workflow**
**Operation ID:** `actions/list-workflow-runs`

List all workflow runs for a workflow. You can replace `workflow_id` with the workflow file name. For example, you could use `main.yaml`. You can use parameters to narrow the list of results. For more information about using parameters, see [Parameters](https://docs.github.com/rest/guides/getting-started-with-the-rest-api#parameters).

Anyone with read access to the repository can use this endpoint

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

This endpoint will return up to 1,000 results for each search when using the following parameters: `actor`, `branch`, `check_suite_id`, `created`, `event`, `head_sha`, `status`.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

