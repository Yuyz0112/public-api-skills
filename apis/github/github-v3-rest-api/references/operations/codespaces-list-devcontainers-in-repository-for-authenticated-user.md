# GET /repos/{owner}/{repo}/codespaces/devcontainers

**Resource:** [codespaces](../resources/codespaces.md)
**List devcontainer configurations in a repository for the authenticated user**
**Operation ID:** `codespaces/list-devcontainers-in-repository-for-authenticated-user`

Lists the devcontainer.json files associated with a specified repository and the authenticated user. These files
specify launchpoint configurations for codespaces created within the repository.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

