# POST /orgs/{org}/codespaces/access/selected_users

**Resource:** [codespaces](../resources/codespaces.md)
**Add users to Codespaces access for an organization**
**Operation ID:** `codespaces/set-codespaces-access-users`
⚠️ **Deprecated**

Codespaces for the specified users will be billed to the organization.

To use this endpoint, the access settings for the organization must be set to `selected_members`.
For information on how to change this setting, see "[Manage access control for organization codespaces](https://docs.github.com/rest/codespaces/organizations#manage-access-control-for-organization-codespaces)."

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

