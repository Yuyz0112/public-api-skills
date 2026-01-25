# POST /repos/{owner}/{repo}/deployments/{deployment_id}/statuses

**Resource:** [repos](../resources/repos.md)
**Create a deployment status**
**Operation ID:** `repos/create-deployment-status`

Users with `push` access can create deployment statuses for a given deployment.

OAuth app tokens and personal access tokens (classic) need the `repo_deployment` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 422 | (reference) |

**Success Response Schema:**

[deployment-status](../schemas/deployment-status/deployment-status.md)

