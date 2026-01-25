# PUT /orgs/{org}/codespaces/access

**Resource:** [codespaces](../resources/codespaces.md)
**Manage access control for organization codespaces**
**Operation ID:** `codespaces/set-codespaces-access`
⚠️ **Deprecated**

Sets which users can access codespaces in an organization. This is synonymous with granting or revoking codespaces access permissions for users according to the visibility.
OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response when successfully modifying permissions. |
| 304 | (reference) |
| 400 | Users are neither members nor collaborators of this organization. |
| 404 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

