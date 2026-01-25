# PUT /repos/{owner}/{repo}/actions/runners/{runner_id}/labels

**Resource:** [actions](../resources/actions.md)
**Set custom labels for a self-hosted runner for a repository**
**Operation ID:** `actions/set-custom-labels-for-self-hosted-runner-for-repo`

Remove all previous custom labels and set the new custom labels for a specific
self-hosted runner configured in a repository.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

