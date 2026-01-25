# GET /repos/{owner}/{repo}/deployments

**Resource:** [repos](../resources/repos.md)
**List deployments**
**Operation ID:** `repos/list-deployments`

Simple filtering of deployments is available via query parameters:

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sha` | query | string | No | The SHA recorded at creation time. |
| `ref` | query | string | No | The name of the ref. This can be a branch, tag, or SHA. |
| `task` | query | string | No | The name of the task for the deployment (e.g., `deploy` or `deploy:migrations`). |
| `environment` | query | string | No | The name of the environment that was deployed to (e.g., `staging` or `production`). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [deployment](../schemas/deployment/deployment.md)

