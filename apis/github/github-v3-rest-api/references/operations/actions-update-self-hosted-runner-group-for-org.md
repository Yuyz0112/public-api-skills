# PATCH /orgs/{org}/actions/runner-groups/{runner_group_id}

**Resource:** [actions](../resources/actions.md)
**Update a self-hosted runner group for an organization**
**Operation ID:** `actions/update-self-hosted-runner-group-for-org`

Updates the `name` and `visibility` of a self-hosted runner group in an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[runner-groups-org](../schemas/runner-groups-org/runner-groups-org.md)

