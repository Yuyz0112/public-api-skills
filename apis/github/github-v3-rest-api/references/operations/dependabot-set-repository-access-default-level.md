# PUT /organizations/{org}/dependabot/repository-access/default-level

**Resource:** [dependabot](../resources/dependabot.md)
**Set the default repository access level for Dependabot**
**Operation ID:** `dependabot/set-repository-access-default-level`

Sets the default level of repository access Dependabot will have while performing an update.  Available values are:
- 'public' - Dependabot will only have access to public repositories, unless access is explicitly granted to non-public repositories.
- 'internal' - Dependabot will only have access to public and internal repositories, unless access is explicitly granted to private repositories.

Unauthorized users will not see the existence of this endpoint.

This operation supports both server-to-server and user-to-server access.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |
| 404 | (reference) |

