# POST /accounts/{account_id}/pages/projects/{project_name}/deployments/{deployment_id}/rollback

**Resource:** [Pages Deployment](../resources/Pages-Deployment.md)
**Rollback deployment**
**Operation ID:** `pages-deployment-rollback-deployment`

Rollback the production deployment to a previous deployment. You can only rollback to succesful builds on production.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deployment_id` | path | pages_identifier | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rollback deployment response. |
| 4XX | Rollback deployment response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
