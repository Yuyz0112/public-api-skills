# GET /repos/{owner}/{repo}/codespaces/machines

**Resource:** [codespaces](../resources/codespaces.md)
**List available machine types for a repository**
**Operation ID:** `codespaces/repo-machines-for-authenticated-user`

List the machine types available for a given repository based on its configuration.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `location` | query | string | No | The location to check for available machines. Assigned by IP if not provided. |
| `client_ip` | query | string | No | IP for location auto-detection when proxying a request |
| `ref` | query | string | No | The branch or commit to check for prebuild availability and devcontainer restrictions. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

