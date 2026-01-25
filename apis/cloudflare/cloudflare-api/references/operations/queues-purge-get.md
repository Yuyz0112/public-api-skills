# GET /accounts/{account_id}/queues/{queue_id}/purge

**Resource:** [Queue](../resources/Queue.md)
**Get Queue Purge Status**
**Operation ID:** `queues-purge-get`

Get details about a Queue's purge status.

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
