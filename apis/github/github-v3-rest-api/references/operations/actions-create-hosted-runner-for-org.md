# POST /orgs/{org}/actions/hosted-runners

**Resource:** [actions](../resources/actions.md)
**Create a GitHub-hosted runner for an organization**
**Operation ID:** `actions/create-hosted-runner-for-org`

Creates a GitHub-hosted runner for an organization.
OAuth tokens and personal access tokens (classic) need the `manage_runners:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[actions-hosted-runner](../schemas/actions-hosted-runner/actions-hosted-runner.md)

