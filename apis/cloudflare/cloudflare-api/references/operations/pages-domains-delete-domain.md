# DELETE /accounts/{account_id}/pages/projects/{project_name}/domains/{domain_name}

**Resource:** [Pages Domains](../resources/Pages-Domains.md)
**Delete domain**
**Operation ID:** `pages-domains-delete-domain`

Delete a Pages project's domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain_name` | path | pages_domain_name | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete domain response. |
| 4XX | Delete domain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
