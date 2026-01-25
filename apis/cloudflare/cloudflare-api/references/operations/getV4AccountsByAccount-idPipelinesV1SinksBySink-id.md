# GET /accounts/{account_id}/pipelines/v1/sinks/{sink_id}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Get Sink Details**
**Operation ID:** `getV4AccountsByAccount_idPipelinesV1SinksBySink_id`

Get Sink Details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `sink_id` | path | cloudflare-pipelines_workers-pipelines-sink-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates that Sink was retrieved. |
| 4XX | Indicates an error in listing Sinks. |

## Security

- **api_token**
- **api_email**
- **api_key**
