# GET /repos/{owner}/{repo}/environments/{environment_name}/secrets

**Resource:** [actions](../resources/actions.md)
**List environment secrets**
**Operation ID:** `actions/list-environment-secrets`

Lists all secrets available in an environment without revealing their
encrypted values.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

