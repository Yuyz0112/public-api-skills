# GET /accounts/{account_id}/builds/repos/{provider_type}/{provider_account_id}/{repo_id}/config_autofill

**Resource:** [GitHub Integration](../resources/GitHub-Integration.md)
**Get repository configuration autofill**
**Operation ID:** `getWorkerConfigAutofill`

Analyze repository for automatic configuration detection

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `provider_type` | path | builds_SCMProviderType | Yes | SCM provider type |
| `provider_account_id` | path | string | Yes | Provider account identifier |
| `repo_id` | path | string | Yes | Repository identifier |
| `branch` | query | string | Yes | Git branch to analyze |
| `root_directory` | query | string | No | Root directory path |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Configuration autofill data retrieved successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
