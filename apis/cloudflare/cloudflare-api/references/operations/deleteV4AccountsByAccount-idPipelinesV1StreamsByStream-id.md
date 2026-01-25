# DELETE /accounts/{account_id}/pipelines/v1/streams/{stream_id}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Delete Stream**
**Operation ID:** `deleteV4AccountsByAccount_idPipelinesV1StreamsByStream_id`

Delete Stream in Account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `force` | query | string | No |  |
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `stream_id` | path | cloudflare-pipelines_workers-pipelines-stream-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully deleted Stream. |
| 4XX | Indicates an error in listing Streams. |

## Security

- **api_token**
- **api_email**
- **api_key**
