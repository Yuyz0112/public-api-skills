# PUT /orgs/{org}/actions/permissions/self-hosted-runners

**Resource:** [actions](../resources/actions.md)
**Set self-hosted runners settings for an organization**
**Operation ID:** `actions/set-self-hosted-runners-permissions-organization`

Sets the settings for self-hosted runners for an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope or the "Actions policies" fine-grained permission to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | No content |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

