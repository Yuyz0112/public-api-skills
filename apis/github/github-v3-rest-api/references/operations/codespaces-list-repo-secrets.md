# GET /repos/{owner}/{repo}/codespaces/secrets

**Resource:** [codespaces](../resources/codespaces.md)
**List repository secrets**
**Operation ID:** `codespaces/list-repo-secrets`

Lists all development environment secrets available in a repository without revealing their encrypted
values.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

