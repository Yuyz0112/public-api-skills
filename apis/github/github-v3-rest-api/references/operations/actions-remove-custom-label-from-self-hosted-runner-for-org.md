# DELETE /orgs/{org}/actions/runners/{runner_id}/labels/{name}

**Resource:** [actions](../resources/actions.md)
**Remove a custom label from a self-hosted runner for an organization**
**Operation ID:** `actions/remove-custom-label-from-self-hosted-runner-for-org`

Remove a custom label from a self-hosted runner configured
in an organization. Returns the remaining labels from the runner.

This endpoint returns a `404 Not Found` status if the custom label is not
present on the runner.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

