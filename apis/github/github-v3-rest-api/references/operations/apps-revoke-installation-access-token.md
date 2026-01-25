# DELETE /installation/token

**Resource:** [apps](../resources/apps.md)
**Revoke an installation access token**
**Operation ID:** `apps/revoke-installation-access-token`

Revokes the installation token you're using to authenticate as an installation and access this endpoint.

Once an installation token is revoked, the token is invalidated and cannot be used. Other endpoints that require the revoked installation token must have a new installation token to work. You can create a new token using the "[Create an installation access token for an app](https://docs.github.com/rest/apps/apps#create-an-installation-access-token-for-an-app)" endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

