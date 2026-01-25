# GET /orgs/{org}/actions/permissions/self-hosted-runners/repositories

**Resource:** [actions](../resources/actions.md)
**List repositories allowed to use self-hosted runners in an organization**
**Operation ID:** `actions/list-selected-repositories-self-hosted-runners-organization`

Lists repositories that are allowed to use self-hosted runners in an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope or the "Actions policies" fine-grained permission to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

