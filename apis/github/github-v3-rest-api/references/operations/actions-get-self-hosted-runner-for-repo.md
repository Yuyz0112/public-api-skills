# GET /repos/{owner}/{repo}/actions/runners/{runner_id}

**Resource:** [actions](../resources/actions.md)
**Get a self-hosted runner for a repository**
**Operation ID:** `actions/get-self-hosted-runner-for-repo`

Gets a specific self-hosted runner configured in a repository.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[runner](../schemas/runner/runner.md)

