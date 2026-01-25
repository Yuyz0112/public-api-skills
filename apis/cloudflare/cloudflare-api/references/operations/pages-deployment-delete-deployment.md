# DELETE /accounts/{account_id}/pages/projects/{project_name}/deployments/{deployment_id}

**Resource:** [Pages Deployment](../resources/Pages-Deployment.md)
**Delete deployment**
**Operation ID:** `pages-deployment-delete-deployment`

Delete a deployment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deployment_id` | path | pages_identifier | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete deployment response. |
| 4XX | Delete deployment response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
