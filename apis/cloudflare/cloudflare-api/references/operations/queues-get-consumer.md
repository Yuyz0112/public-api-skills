# GET /accounts/{account_id}/queues/{queue_id}/consumers/{consumer_id}

**Resource:** [Queue](../resources/Queue.md)
**Get Queue Consumer**
**Operation ID:** `queues-get-consumer`

Fetches the consumer for a queue by consumer id

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `consumer_id` | path | mq_identifier | Yes |  |
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Queue Consumer response. |
| 4XX | Get Queue Consumer response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
