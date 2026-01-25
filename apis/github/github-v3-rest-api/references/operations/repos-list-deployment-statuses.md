# GET /repos/{owner}/{repo}/deployments/{deployment_id}/statuses

**Resource:** [repos](../resources/repos.md)
**List deployment statuses**
**Operation ID:** `repos/list-deployment-statuses`

Users with pull access can view deployment statuses for a deployment:

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [deployment-status](../schemas/deployment-status/deployment-status.md)

