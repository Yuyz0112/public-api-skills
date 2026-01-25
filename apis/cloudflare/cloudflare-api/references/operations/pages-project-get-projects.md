# GET /accounts/{account_id}/pages/projects

**Resource:** [Pages Project](../resources/Pages-Project.md)
**Get projects**
**Operation ID:** `pages-project-get-projects`

Fetch a list of all user projects.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | pages_identifier | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get projects response. |
| 4XX | Get projects response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
