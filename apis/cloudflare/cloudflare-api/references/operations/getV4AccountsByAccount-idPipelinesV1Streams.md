# GET /accounts/{account_id}/pipelines/v1/streams

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**List Streams**
**Operation ID:** `getV4AccountsByAccount_idPipelinesV1Streams`

List/Filter Streams in Account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `pipeline_id` | query | cloudflare-pipelines_workers-pipelines-pipeline-id | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully created Stream. |
| 4XX | Indicates an error in listing Streams. |

## Security

- **api_token**
- **api_email**
- **api_key**
