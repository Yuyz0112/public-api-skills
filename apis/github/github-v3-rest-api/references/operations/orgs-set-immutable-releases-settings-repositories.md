# PUT /orgs/{org}/settings/immutable-releases/repositories

**Resource:** [orgs](../resources/orgs.md)
**Set selected repositories for immutable releases enforcement**
**Operation ID:** `orgs/set-immutable-releases-settings-repositories`

Replaces all repositories that have been selected for immutable releases enforcement in an organization. To use this endpoint, the organization immutable releases policy for `enforced_repositories` must be configured to `selected`.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

