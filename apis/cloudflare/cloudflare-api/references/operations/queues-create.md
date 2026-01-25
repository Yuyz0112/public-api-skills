# POST /accounts/{account_id}/queues

**Resource:** [Queue](../resources/Queue.md)
**Create Queue**
**Operation ID:** `queues-create`

Create a new queue

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mq_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Created Queue |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
