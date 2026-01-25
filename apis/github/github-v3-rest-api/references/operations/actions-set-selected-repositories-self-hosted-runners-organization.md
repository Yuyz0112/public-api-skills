# PUT /orgs/{org}/actions/permissions/self-hosted-runners/repositories

**Resource:** [actions](../resources/actions.md)
**Set repositories allowed to use self-hosted runners in an organization**
**Operation ID:** `actions/set-selected-repositories-self-hosted-runners-organization`

Sets repositories that are allowed to use self-hosted runners in an organization.

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
| 422 | (reference) |

