# PATCH /accounts/{account_id}/queues/{queue_id}

**Resource:** [Queue](../resources/Queue.md)
**Update Queue**
**Operation ID:** `queues-update-partial`

Updates a Queue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [mq_queue](../schemas/mq/mq-queue.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Updated Queue |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
