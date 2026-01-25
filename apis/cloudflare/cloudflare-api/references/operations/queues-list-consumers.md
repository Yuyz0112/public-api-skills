# GET /accounts/{account_id}/queues/{queue_id}/consumers

**Resource:** [Queue](../resources/Queue.md)
**List Queue Consumers**
**Operation ID:** `queues-list-consumers`

Returns the consumers for a Queue

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | All consumers attached to this Queue |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
