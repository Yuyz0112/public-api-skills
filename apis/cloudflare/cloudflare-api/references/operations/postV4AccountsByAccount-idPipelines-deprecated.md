# POST /accounts/{account_id}/pipelines

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**[DEPRECATED] Create Pipeline**
**Operation ID:** `postV4AccountsByAccount_idPipelines_deprecated`
⚠️ **Deprecated**

[DEPRECATED] Create a new pipeline. Use the new /pipelines/v1/pipelines endpoint instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | [DEPRECATED] Indicates a successfully created pipeline. Use /pipelines/v1/pipelines instead. |
| 4XX | Indicates an error in creating a pipeline. |

## Security

- **api_token**
- **api_email**
- **api_key**
