# POST /accounts/{account_id}/queues/{queue_id}/messages/batch

**Resource:** [Queue](../resources/Queue.md)
**Push Message Batch**
**Operation ID:** `queues-push-messages`

Push a batch of message to a Queue

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [mq_queue-batch](../schemas/mq/mq-queue-batch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful batch ingestion |
| 4XX | Failure response |

**Success Response Schema:**

[mq_api-v4-success](../schemas/mq/mq-api-v4-success.md)

## Security

- **api_email**
- **api_key**
- **api_token**
