# DELETE /repos/{owner}/{repo}/actions/runners/{runner_id}/labels/{name}

**Resource:** [actions](../resources/actions.md)
**Remove a custom label from a self-hosted runner for a repository**
**Operation ID:** `actions/remove-custom-label-from-self-hosted-runner-for-repo`

Remove a custom label from a self-hosted runner configured
in a repository. Returns the remaining labels from the runner.

This endpoint returns a `404 Not Found` status if the custom label is not
present on the runner.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

