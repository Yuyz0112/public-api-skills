# POST /accounts/{account_id}/pages/projects/{project_name}/deployments/{deployment_id}/retry

**Resource:** [Pages Deployment](../resources/Pages-Deployment.md)
**Retry deployment**
**Operation ID:** `pages-deployment-retry-deployment`

Retry a previous deployment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deployment_id` | path | pages_identifier | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retry deployment response. |
| 4XX | Retry deployment response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
