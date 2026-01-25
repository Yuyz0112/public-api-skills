# GET /repos/{owner}/{repo}/deployments/{deployment_id}/statuses/{status_id}

**Resource:** [repos](../resources/repos.md)
**Get a deployment status**
**Operation ID:** `repos/get-deployment-status`

Users with pull access can view a deployment status for a deployment:

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `status_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[deployment-status](../schemas/deployment-status/deployment-status.md)

