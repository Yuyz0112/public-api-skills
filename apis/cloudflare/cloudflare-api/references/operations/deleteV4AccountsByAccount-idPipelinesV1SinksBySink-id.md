# DELETE /accounts/{account_id}/pipelines/v1/sinks/{sink_id}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Delete Sink**
**Operation ID:** `deleteV4AccountsByAccount_idPipelinesV1SinksBySink_id`

Delete Pipeline in Account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `sink_id` | path | cloudflare-pipelines_workers-pipelines-sink-id | Yes |  |
| `force` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully deleted Sink. |
| 4XX | Indicates an error in listing Sinks. |

## Security

- **api_token**
- **api_email**
- **api_key**
