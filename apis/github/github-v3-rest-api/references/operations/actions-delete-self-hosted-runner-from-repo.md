# DELETE /repos/{owner}/{repo}/actions/runners/{runner_id}

**Resource:** [actions](../resources/actions.md)
**Delete a self-hosted runner from a repository**
**Operation ID:** `actions/delete-self-hosted-runner-from-repo`

Forces the removal of a self-hosted runner from a repository. You can use this endpoint to completely remove the runner when the machine you were using no longer exists.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 422 | (reference) |

