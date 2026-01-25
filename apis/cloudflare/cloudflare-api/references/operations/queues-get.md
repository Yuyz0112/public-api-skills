# GET /accounts/{account_id}/queues/{queue_id}

**Resource:** [Queue](../resources/Queue.md)
**Get Queue**
**Operation ID:** `queues-get`

Get details about a specific queue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | mq_identifier | Yes |  |
| `account_id` | path | mq_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Details of the requested Queue |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
