# GET /accounts/{account_id}/pipelines/v1/sinks

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**List Sinks**
**Operation ID:** `getV4AccountsByAccount_idPipelinesV1Sinks`

List/Filter Sinks in Account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `pipeline_id` | query | string | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates successfully listed Sinks. |
| 4XX | Indicates an error in listing Sinks. |

## Security

- **api_token**
- **api_email**
- **api_key**
