# GET /accounts/{account_id}/pages/projects/{project_name}/deployments

**Resource:** [Pages Deployment](../resources/Pages-Deployment.md)
**Get deployments**
**Operation ID:** `pages-deployment-get-deployments`

Fetch a list of project deployments.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |
| `env` | query | enum: production, preview | No |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get deployments response. |
| 4XX | Get deployments response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
