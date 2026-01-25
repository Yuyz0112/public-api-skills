# POST /accounts/{account_id}/queues/{queue_id}/messages/ack

**Resource:** [Queue](../resources/Queue.md)
**Acknowledge + Retry Queue Messages**
**Operation ID:** `queues-ack-messages`

Acknowledge + Retry messages from a Queue

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Details of ACKs and retries |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
