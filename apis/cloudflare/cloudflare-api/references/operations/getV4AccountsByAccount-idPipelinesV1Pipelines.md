# GET /accounts/{account_id}/pipelines/v1/pipelines

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**List Pipelines**
**Operation ID:** `getV4AccountsByAccount_idPipelinesV1Pipelines`

List/Filter Pipelines in Account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully listed Pipelines. |
| 4XX | Indicates an error in listing Pipelines. |

## Security

- **api_token**
- **api_email**
- **api_key**
