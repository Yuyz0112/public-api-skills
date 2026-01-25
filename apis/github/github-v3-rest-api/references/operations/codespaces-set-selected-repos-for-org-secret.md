# PUT /orgs/{org}/codespaces/secrets/{secret_name}/repositories

**Resource:** [codespaces](../resources/codespaces.md)
**Set selected repositories for an organization secret**
**Operation ID:** `codespaces/set-selected-repos-for-org-secret`

Replaces all repositories for an organization development environment secret when the `visibility`
for repository access is set to `selected`. The visibility is set when you [Create
or update an organization secret](https://docs.github.com/rest/codespaces/organization-secrets#create-or-update-an-organization-secret).

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |
| 409 | Conflict when visibility type not set to selected |

