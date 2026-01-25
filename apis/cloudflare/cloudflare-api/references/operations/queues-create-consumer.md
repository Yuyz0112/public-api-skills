# POST /accounts/{account_id}/queues/{queue_id}/consumers

**Resource:** [Queue](../resources/Queue.md)
**Create a Queue Consumer**
**Operation ID:** `queues-create-consumer`

Creates a new consumer for a Queue

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
| 200 | Create Queue Consumer response. |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
