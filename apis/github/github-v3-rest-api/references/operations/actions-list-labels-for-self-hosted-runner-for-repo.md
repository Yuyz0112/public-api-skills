# GET /repos/{owner}/{repo}/actions/runners/{runner_id}/labels

**Resource:** [actions](../resources/actions.md)
**List labels for a self-hosted runner for a repository**
**Operation ID:** `actions/list-labels-for-self-hosted-runner-for-repo`

Lists all labels for a self-hosted runner configured in a repository.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |

