# GET /orgs/{org}/codespaces/secrets/{secret_name}/repositories

**Resource:** [codespaces](../resources/codespaces.md)
**List selected repositories for an organization secret**
**Operation ID:** `codespaces/list-selected-repos-for-org-secret`

Lists all repositories that have been selected when the `visibility`
for repository access to a secret is set to `selected`.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

