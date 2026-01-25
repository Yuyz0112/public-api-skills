# GET /orgs/{org}/actions/secrets/{secret_name}/repositories

**Resource:** [actions](../resources/actions.md)
**List selected repositories for an organization secret**
**Operation ID:** `actions/list-selected-repos-for-org-secret`

Lists all repositories that have been selected when the `visibility`
for repository access to a secret is set to `selected`.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

