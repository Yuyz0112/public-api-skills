# GET /accounts/{account_id}/pipelines/{pipeline_name}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**[DEPRECATED] Get Pipeline**
**Operation ID:** `getV4AccountsByAccount_idPipelinesByPipeline_name_deprecated`
⚠️ **Deprecated**

[DEPRECATED] Get configuration of a pipeline. Use the new /pipelines/v1/pipelines endpoint instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `pipeline_name` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | [DEPRECATED] Describes the configuration of a pipeline. |
| 404 | Indicates that the pipeline was not found. |

## Security

- **api_token**
- **api_email**
- **api_key**
