# GET /accounts/{account_id}/pipelines/v1/streams/{stream_id}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Get Stream Details**
**Operation ID:** `getV4AccountsByAccount_idPipelinesV1StreamsByStream_id`

Get Stream Details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `stream_id` | path | cloudflare-pipelines_workers-pipelines-stream-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully retrieved Stream. |
| 4XX | Indicates an error in retrieving Stream. |

## Security

- **api_token**
- **api_email**
- **api_key**
