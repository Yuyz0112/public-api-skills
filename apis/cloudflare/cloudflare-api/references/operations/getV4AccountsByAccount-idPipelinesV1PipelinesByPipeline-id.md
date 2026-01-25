# GET /accounts/{account_id}/pipelines/v1/pipelines/{pipeline_id}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Get Pipeline Details**
**Operation ID:** `getV4AccountsByAccount_idPipelinesV1PipelinesByPipeline_id`

Get Pipelines Details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `pipeline_id` | path | cloudflare-pipelines_workers-pipelines-pipeline-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully retrieved Pipeline. |
| 4XX | Indicates an error in retrieving Pipelines. |

## Security

- **api_token**
- **api_email**
- **api_key**
