# POST /accounts/{account_id}/pages/projects/{project_name}/domains

**Resource:** [Pages Domains](../resources/Pages-Domains.md)
**Add domain**
**Operation ID:** `pages-domains-add-domain`

Add a new domain for the Pages project.

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
| 200 | Add domain response. |
| 4XX | Add domain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
