# DELETE /accounts/{account_id}/pipelines/{pipeline_name}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**[DEPRECATED] Delete Pipeline**
**Operation ID:** `deleteV4AccountsByAccount_idPipelinesByPipeline_name_deprecated`
⚠️ **Deprecated**

[DEPRECATED] Delete a pipeline. Use the new /pipelines/v1/pipelines endpoint instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `pipeline_name` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | [DEPRECATED] Indicates a successfully deleted pipeline. |
| 4XX | Indicates an error in deleting a pipeline. |

## Security

- **api_token**
- **api_email**
- **api_key**
