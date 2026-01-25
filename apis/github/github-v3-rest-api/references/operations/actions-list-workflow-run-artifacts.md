# GET /repos/{owner}/{repo}/actions/runs/{run_id}/artifacts

**Resource:** [actions](../resources/actions.md)
**List workflow run artifacts**
**Operation ID:** `actions/list-workflow-run-artifacts`

Lists artifacts for a workflow run.

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

