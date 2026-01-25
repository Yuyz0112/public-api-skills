# DELETE /accounts/{account_id}/queues/{queue_id}/consumers/{consumer_id}

**Resource:** [Queue](../resources/Queue.md)
**Delete Queue Consumer**
**Operation ID:** `queues-delete-consumer`

Deletes the consumer for a queue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `consumer_id` | path | mq_identifier | Yes |  |
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful consumer delete |
| 4XX | Failure response |

**Success Response Schema:**

[mq_api-v4-success](../schemas/mq/mq-api-v4-success.md)

## Security

- **api_email**
- **api_key**
- **api_token**
