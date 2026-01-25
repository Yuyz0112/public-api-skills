# DELETE /accounts/{account_id}/pages/projects/{project_name}

**Resource:** [Pages Project](../resources/Pages-Project.md)
**Delete project**
**Operation ID:** `pages-project-delete-project`

Delete a project by name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete project response. |
| 4XX | Delete project response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
