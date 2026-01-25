# PUT /orgs/{org}/actions/permissions/self-hosted-runners/repositories/{repository_id}

**Resource:** [actions](../resources/actions.md)
**Add a repository to the list of repositories allowed to use self-hosted runners in an organization**
**Operation ID:** `actions/enable-selected-repository-self-hosted-runners-organization`

Adds a repository to the list of repositories that are allowed to use self-hosted runners in an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope or the "Actions policies" fine-grained permission to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | No content |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

