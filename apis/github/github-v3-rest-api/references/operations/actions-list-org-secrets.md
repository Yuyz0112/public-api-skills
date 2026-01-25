# GET /orgs/{org}/actions/secrets

**Resource:** [actions](../resources/actions.md)
**List organization secrets**
**Operation ID:** `actions/list-org-secrets`

Lists all secrets available in an organization without revealing their
encrypted values.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

