# POST /accounts/{account_id}/pages/projects/{project_name}/deployments

**Resource:** [Pages Deployment](../resources/Pages-Deployment.md)
**Create deployment**
**Operation ID:** `pages-deployment-create-deployment`

Start a new deployment from production. The repository and account must have already been authorized on the Cloudflare Pages dashboard.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create deployment response. |
| 4XX | Create deployment response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
