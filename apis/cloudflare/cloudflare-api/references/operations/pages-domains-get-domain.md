# GET /accounts/{account_id}/pages/projects/{project_name}/domains/{domain_name}

**Resource:** [Pages Domains](../resources/Pages-Domains.md)
**Get domain**
**Operation ID:** `pages-domains-get-domain`

Fetch a single domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain_name` | path | pages_domain_name | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get domain response. |
| 4XX | Get domain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
