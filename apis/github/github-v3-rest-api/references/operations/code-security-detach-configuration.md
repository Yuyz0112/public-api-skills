# DELETE /orgs/{org}/code-security/configurations/detach

**Resource:** [code-security](../resources/code-security.md)
**Detach configurations from repositories**
**Operation ID:** `code-security/detach-configuration`

Detach code security configuration(s) from a set of repositories.
Repositories will retain their settings but will no longer be associated with the configuration.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

