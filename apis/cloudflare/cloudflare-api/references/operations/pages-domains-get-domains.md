# GET /accounts/{account_id}/pages/projects/{project_name}/domains

**Resource:** [Pages Domains](../resources/Pages-Domains.md)
**Get domains**
**Operation ID:** `pages-domains-get-domains`

Fetch a list of all domains associated with a Pages project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get domains response. |
| 4XX | Get domains response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
