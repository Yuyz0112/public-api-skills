# DELETE /repos/{owner}/{repo}/actions/runs/{run_id}

**Resource:** [actions](../resources/actions.md)
**Delete a workflow run**
**Operation ID:** `actions/delete-workflow-run`

Deletes a specific workflow run.

Anyone with write access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

