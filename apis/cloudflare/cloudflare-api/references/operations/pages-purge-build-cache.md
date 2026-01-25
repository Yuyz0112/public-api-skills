# POST /accounts/{account_id}/pages/projects/{project_name}/purge_build_cache

**Resource:** [Pages Build Cache](../resources/Pages-Build-Cache.md)
**Purge build cache**
**Operation ID:** `pages-purge-build-cache`

Purge all cached build artifacts for a Pages project

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_name` | path | pages_project_name | Yes |  |
| `account_id` | path | pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Purge build cache response. |
| 4XX | Purge build cache failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
