# POST /accounts/{account_id}/pipelines/v1/validate_sql

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Validate SQL**
**Operation ID:** `postV4AccountsByAccount_idPipelinesV1Validate_sql`

Validate Arroyo SQL.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates SQL validation success. |
| 4XX | Indicates SQL validation failed. |

## Security

- **api_token**
- **api_email**
- **api_key**
