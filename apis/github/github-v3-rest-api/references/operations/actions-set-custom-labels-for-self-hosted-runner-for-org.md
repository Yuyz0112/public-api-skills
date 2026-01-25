# PUT /orgs/{org}/actions/runners/{runner_id}/labels

**Resource:** [actions](../resources/actions.md)
**Set custom labels for a self-hosted runner for an organization**
**Operation ID:** `actions/set-custom-labels-for-self-hosted-runner-for-org`

Remove all previous custom labels and set the new custom labels for a specific
self-hosted runner configured in an organization.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

