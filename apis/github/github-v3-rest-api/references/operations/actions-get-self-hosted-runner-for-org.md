# GET /orgs/{org}/actions/runners/{runner_id}

**Resource:** [actions](../resources/actions.md)
**Get a self-hosted runner for an organization**
**Operation ID:** `actions/get-self-hosted-runner-for-org`

Gets a specific self-hosted runner configured in an organization.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[runner](../schemas/runner/runner.md)

