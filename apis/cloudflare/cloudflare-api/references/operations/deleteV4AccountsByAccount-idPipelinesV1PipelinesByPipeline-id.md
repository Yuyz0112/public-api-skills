# DELETE /accounts/{account_id}/pipelines/v1/pipelines/{pipeline_id}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Delete Pipelines**
**Operation ID:** `deleteV4AccountsByAccount_idPipelinesV1PipelinesByPipeline_id`

Delete Pipeline in Account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `pipeline_id` | path | cloudflare-pipelines_workers-pipelines-pipeline-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully deleted Pipeline. |
| 4XX | Indicates an error in listing Pipelines. |

## Security

- **api_token**
- **api_email**
- **api_key**
