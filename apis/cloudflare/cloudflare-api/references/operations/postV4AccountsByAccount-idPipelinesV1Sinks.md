# POST /accounts/{account_id}/pipelines/v1/sinks

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Create Sink**
**Operation ID:** `postV4AccountsByAccount_idPipelinesV1Sinks`

Create a new Sink.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully created Sink. |
| 4XX | Indicates an error in creating a Sink. |

## Security

- **api_token**
- **api_email**
- **api_key**
