# POST /accounts/{account_id}/pages/projects

**Resource:** [Pages Project](../resources/Pages-Project.md)
**Create project**
**Operation ID:** `pages-project-create-project`

Create a new project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | pages_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create project response. |
| 4XX | Create project response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
