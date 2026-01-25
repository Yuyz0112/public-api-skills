# POST /accounts/{account_id}/queues/{queue_id}/messages/pull

**Resource:** [Queue](../resources/Queue.md)
**Pull Queue Messages**
**Operation ID:** `queues-pull-messages`

Pull a batch of messages from a Queue

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
| 200 | A batch of messages in the Queue |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
