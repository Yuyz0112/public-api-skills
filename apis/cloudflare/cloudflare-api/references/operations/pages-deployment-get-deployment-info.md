# GET /accounts/{account_id}/pages/projects/{project_name}/deployments/{deployment_id}

**Resource:** [Pages Deployment](../resources/Pages-Deployment.md)
**Get deployment info**
**Operation ID:** `pages-deployment-get-deployment-info`

Fetch information about a deployment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deployment_id` | path | pages_identifier | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get deployment info response. |
| 4XX | Get deployment info response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
