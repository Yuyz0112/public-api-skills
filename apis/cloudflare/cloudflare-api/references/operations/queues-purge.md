# POST /accounts/{account_id}/queues/{queue_id}/purge

**Resource:** [Queue](../resources/Queue.md)
**Purge Queue**
**Operation ID:** `queues-purge`

Deletes all messages from the Queue.

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
| 200 | Updated Queue |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
