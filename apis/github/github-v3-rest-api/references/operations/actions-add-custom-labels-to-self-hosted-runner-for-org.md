# POST /orgs/{org}/actions/runners/{runner_id}/labels

**Resource:** [actions](../resources/actions.md)
**Add custom labels to a self-hosted runner for an organization**
**Operation ID:** `actions/add-custom-labels-to-self-hosted-runner-for-org`

Adds custom labels to a self-hosted runner configured in an organization.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

