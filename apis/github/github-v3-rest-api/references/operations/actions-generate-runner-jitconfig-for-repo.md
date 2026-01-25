# POST /repos/{owner}/{repo}/actions/runners/generate-jitconfig

**Resource:** [actions](../resources/actions.md)
**Create configuration for a just-in-time runner for a repository**
**Operation ID:** `actions/generate-runner-jitconfig-for-repo`

Generates a configuration that can be passed to the runner application at startup.

The authenticated user must have admin access to the repository.

OAuth tokens and personal access tokens (classic) need the`repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

