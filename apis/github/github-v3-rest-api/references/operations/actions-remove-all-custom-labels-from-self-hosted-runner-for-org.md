# DELETE /orgs/{org}/actions/runners/{runner_id}/labels

**Resource:** [actions](../resources/actions.md)
**Remove all custom labels from a self-hosted runner for an organization**
**Operation ID:** `actions/remove-all-custom-labels-from-self-hosted-runner-for-org`

Remove all custom labels from a self-hosted runner configured in an
organization. Returns the remaining read-only labels from the runner.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |

