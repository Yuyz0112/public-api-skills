# DELETE /orgs/{org}/actions/runner-groups/{runner_group_id}/repositories/{repository_id}

**Resource:** [actions](../resources/actions.md)
**Remove repository access to a self-hosted runner group in an organization**
**Operation ID:** `actions/remove-repo-access-to-self-hosted-runner-group-in-org`

Removes a repository from the list of selected repositories that can access a self-hosted runner group. The runner group must have `visibility` set to `selected`. For more information, see "[Create a self-hosted runner group for an organization](#create-a-self-hosted-runner-group-for-an-organization)."

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

