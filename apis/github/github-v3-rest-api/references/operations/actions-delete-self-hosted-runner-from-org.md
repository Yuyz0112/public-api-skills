# DELETE /orgs/{org}/actions/runners/{runner_id}

**Resource:** [actions](../resources/actions.md)
**Delete a self-hosted runner from an organization**
**Operation ID:** `actions/delete-self-hosted-runner-from-org`

Forces the removal of a self-hosted runner from an organization. You can use this endpoint to completely remove the runner when the machine you were using no longer exists.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 422 | (reference) |

