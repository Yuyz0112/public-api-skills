# POST /accounts/{account_id}/pipelines/v1/streams

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Create Stream**
**Operation ID:** `postV4AccountsByAccount_idPipelinesV1Streams`

Create a new Stream.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully created Stream. |
| 4XX | Indicates an error in creating a Stream. |

## Security

- **api_token**
- **api_email**
- **api_key**
