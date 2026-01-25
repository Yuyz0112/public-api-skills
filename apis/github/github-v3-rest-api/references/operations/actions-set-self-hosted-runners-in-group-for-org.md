# PUT /orgs/{org}/actions/runner-groups/{runner_group_id}/runners

**Resource:** [actions](../resources/actions.md)
**Set self-hosted runners in a group for an organization**
**Operation ID:** `actions/set-self-hosted-runners-in-group-for-org`

Replaces the list of self-hosted runners that are part of an organization runner group.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

