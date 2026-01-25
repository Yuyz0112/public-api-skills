# GET /orgs/{org}/actions/permissions/self-hosted-runners

**Resource:** [actions](../resources/actions.md)
**Get self-hosted runners settings for an organization**
**Operation ID:** `actions/get-self-hosted-runners-permissions-organization`

Gets the settings for self-hosted runners for an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope or the "Actions policies" fine-grained permission to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[self-hosted-runners-settings](../schemas/self-hosted-runners-settings/self-hosted-runners-settings.md)

