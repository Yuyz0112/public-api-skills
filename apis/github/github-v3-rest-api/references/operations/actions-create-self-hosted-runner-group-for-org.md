# POST /orgs/{org}/actions/runner-groups

**Resource:** [actions](../resources/actions.md)
**Create a self-hosted runner group for an organization**
**Operation ID:** `actions/create-self-hosted-runner-group-for-org`

Creates a new self-hosted runner group for an organization.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[runner-groups-org](../schemas/runner-groups-org/runner-groups-org.md)

