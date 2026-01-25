# GET /orgs/{org}/actions/hosted-runners/{hosted_runner_id}

**Resource:** [actions](../resources/actions.md)
**Get a GitHub-hosted runner for an organization**
**Operation ID:** `actions/get-hosted-runner-for-org`

Gets a GitHub-hosted runner configured in an organization.

OAuth app tokens and personal access tokens (classic) need the `manage_runners:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-hosted-runner](../schemas/actions-hosted-runner/actions-hosted-runner.md)

