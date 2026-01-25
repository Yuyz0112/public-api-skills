# PUT /orgs/{org}/actions/runner-groups/{runner_group_id}/repositories

**Resource:** [actions](../resources/actions.md)
**Set repository access for a self-hosted runner group in an organization**
**Operation ID:** `actions/set-repo-access-to-self-hosted-runner-group-in-org`

Replaces the list of repositories that have access to a self-hosted runner group configured in an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

