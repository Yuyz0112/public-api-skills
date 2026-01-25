# GET /repos/{owner}/{repo}/actions/secrets

**Resource:** [actions](../resources/actions.md)
**List repository secrets**
**Operation ID:** `actions/list-repo-secrets`

Lists all secrets available in a repository without revealing their encrypted
values.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

