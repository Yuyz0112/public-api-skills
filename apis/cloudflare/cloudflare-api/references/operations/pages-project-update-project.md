# PATCH /accounts/{account_id}/pages/projects/{project_name}

**Resource:** [Pages Project](../resources/Pages-Project.md)
**Update project**
**Operation ID:** `pages-project-update-project`

Set new attributes for an existing project. Modify environment variables. To delete an environment variable, set the key to null.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update project response. |
| 4XX | Update project response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
