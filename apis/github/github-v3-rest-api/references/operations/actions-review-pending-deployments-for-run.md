# POST /repos/{owner}/{repo}/actions/runs/{run_id}/pending_deployments

**Resource:** [actions](../resources/actions.md)
**Review pending deployments for a workflow run**
**Operation ID:** `actions/review-pending-deployments-for-run`

Approve or reject pending deployments that are waiting on approval by a required reviewer.

Required reviewers with read access to the repository contents and deployments can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [deployment](../schemas/deployment/deployment.md)

