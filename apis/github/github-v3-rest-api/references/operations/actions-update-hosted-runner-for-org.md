# PATCH /orgs/{org}/actions/hosted-runners/{hosted_runner_id}

**Resource:** [actions](../resources/actions.md)
**Update a GitHub-hosted runner for an organization**
**Operation ID:** `actions/update-hosted-runner-for-org`

Updates a GitHub-hosted runner for an organization.
OAuth app tokens and personal access tokens (classic) need the `manage_runners:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-hosted-runner](../schemas/actions-hosted-runner/actions-hosted-runner.md)

