# GET /orgs/{org}/dependabot/secrets/{secret_name}/repositories

**Resource:** [dependabot](../resources/dependabot.md)
**List selected repositories for an organization secret**
**Operation ID:** `dependabot/list-selected-repos-for-org-secret`

Lists all repositories that have been selected when the `visibility`
for repository access to a secret is set to `selected`.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

