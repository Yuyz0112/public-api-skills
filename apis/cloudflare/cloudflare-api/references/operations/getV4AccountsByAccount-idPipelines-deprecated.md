# GET /accounts/{account_id}/pipelines

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**[DEPRECATED] List Pipelines**
**Operation ID:** `getV4AccountsByAccount_idPipelines_deprecated`
⚠️ **Deprecated**

[DEPRECATED] List, filter, and paginate pipelines in an account. Use the new /pipelines/v1/pipelines endpoint instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `search` | query | string | No |  |
| `page` | query | string | No |  |
| `per_page` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | [DEPRECATED] Lists the pipelines. Use /pipelines/v1/pipelines instead. |
| 4XX | Indicates the error trying to list pipelines. |

## Security

- **api_token**
- **api_email**
- **api_key**
