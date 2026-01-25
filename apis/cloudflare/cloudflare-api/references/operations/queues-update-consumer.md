# PUT /accounts/{account_id}/queues/{queue_id}/consumers/{consumer_id}

**Resource:** [Queue](../resources/Queue.md)
**Update Queue Consumer**
**Operation ID:** `queues-update-consumer`

Updates the consumer for a queue, or creates one if it does not exist.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `consumer_id` | path | mq_identifier | Yes |  |
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Queue Consumer response. |
| 4XX | Update Queue Consumer response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
