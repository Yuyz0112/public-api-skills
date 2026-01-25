# GET /repos/{owner}/{repo}/actions/runs/{run_id}/approvals

**Resource:** [actions](../resources/actions.md)
**Get the review history for a workflow run**
**Operation ID:** `actions/get-reviews-for-run`

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [environment-approvals](../schemas/environment-approvals/environment-approvals.md)

