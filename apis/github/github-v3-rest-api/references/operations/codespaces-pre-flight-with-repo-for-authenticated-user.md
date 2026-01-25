# GET /repos/{owner}/{repo}/codespaces/new

**Resource:** [codespaces](../resources/codespaces.md)
**Get default attributes for a codespace**
**Operation ID:** `codespaces/pre-flight-with-repo-for-authenticated-user`

Gets the default attributes for codespaces created by the user with the repository.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ref` | query | string | No | The branch or commit to check for a default devcontainer path. If not specified, the default branch will be checked. |
| `client_ip` | query | string | No | An alternative IP for default location auto-detection, such as when proxying a request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response when a user is able to create codespaces from the repository. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

