# DELETE /orgs/{org}/actions/runner-groups/{runner_group_id}/runners/{runner_id}

**Resource:** [actions](../resources/actions.md)
**Remove a self-hosted runner from a group for an organization**
**Operation ID:** `actions/remove-self-hosted-runner-from-group-for-org`

Removes a self-hosted runner from a group configured in an organization. The runner is then returned to the default group.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

