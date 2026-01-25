# GET /accounts/{account_id}/pages/projects/{project_name}/deployments/{deployment_id}/history/logs

**Resource:** [Pages Deployment](../resources/Pages-Deployment.md)
**Get deployment logs**
**Operation ID:** `pages-deployment-get-deployment-logs`

Fetch deployment logs for a project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deployment_id` | path | pages_identifier | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get deployment logs response. |
| 4XX | Get deployment logs response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
