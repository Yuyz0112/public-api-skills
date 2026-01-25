# GET /orgs/{org}/actions/runner-groups/{runner_group_id}

**Resource:** [actions](../resources/actions.md)
**Get a self-hosted runner group for an organization**
**Operation ID:** `actions/get-self-hosted-runner-group-for-org`

Gets a specific self-hosted runner group for an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[runner-groups-org](../schemas/runner-groups-org/runner-groups-org.md)

