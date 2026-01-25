# PUT /accounts/{account_id}/pipelines/{pipeline_name}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**[DEPRECATED] Update Pipeline**
**Operation ID:** `putV4AccountsByAccount_idPipelinesByPipeline_name_deprecated`
⚠️ **Deprecated**

[DEPRECATED] Update an existing pipeline. Use the new /pipelines/v1/pipelines endpoint instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `pipeline_name` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | [DEPRECATED] Indicates a successfully updated pipeline. |
| 4XX | Indicates an error updating pipeline. |

## Security

- **api_token**
- **api_email**
- **api_key**
