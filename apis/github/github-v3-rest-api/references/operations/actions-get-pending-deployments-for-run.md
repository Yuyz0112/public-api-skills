# GET /repos/{owner}/{repo}/actions/runs/{run_id}/pending_deployments

**Resource:** [actions](../resources/actions.md)
**Get pending deployments for a workflow run**
**Operation ID:** `actions/get-pending-deployments-for-run`

Get all deployment environments for a workflow run that are waiting for protection rules to pass.

Anyone with read access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [pending-deployment](../schemas/pending-deployment/pending-deployment.md)

