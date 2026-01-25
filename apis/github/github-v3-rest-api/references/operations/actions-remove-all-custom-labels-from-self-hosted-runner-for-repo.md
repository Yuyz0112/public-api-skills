# DELETE /repos/{owner}/{repo}/actions/runners/{runner_id}/labels

**Resource:** [actions](../resources/actions.md)
**Remove all custom labels from a self-hosted runner for a repository**
**Operation ID:** `actions/remove-all-custom-labels-from-self-hosted-runner-for-repo`

Remove all custom labels from a self-hosted runner configured in a
repository. Returns the remaining read-only labels from the runner.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |

