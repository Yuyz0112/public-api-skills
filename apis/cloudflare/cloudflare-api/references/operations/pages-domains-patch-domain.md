# PATCH /accounts/{account_id}/pages/projects/{project_name}/domains/{domain_name}

**Resource:** [Pages Domains](../resources/Pages-Domains.md)
**Patch domain**
**Operation ID:** `pages-domains-patch-domain`

Retry the validation status of a single domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain_name` | path | pages_domain_name | Yes |  |
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch domain response. |
| 4XX | Patch domain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
