# GET /repos/{owner}/{repo}/actions/organization-secrets

**Resource:** [actions](../resources/actions.md)
**List repository organization secrets**
**Operation ID:** `actions/list-repo-organization-secrets`

Lists all organization secrets shared with a repository without revealing their encrypted
values.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

