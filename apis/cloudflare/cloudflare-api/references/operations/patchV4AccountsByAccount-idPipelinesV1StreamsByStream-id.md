# PATCH /accounts/{account_id}/pipelines/v1/streams/{stream_id}

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Update Stream**
**Operation ID:** `patchV4AccountsByAccount_idPipelinesV1StreamsByStream_id`

Update a Stream.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |
| `stream_id` | path | cloudflare-pipelines_workers-pipelines-stream-id | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully updated Stream. |
| 4XX | Indicates an error in creating a Stream. |

## Security

- **api_token**
- **api_email**
- **api_key**
