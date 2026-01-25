# GET /accounts/{account_id}/queues

**Resource:** [Queue](../resources/Queue.md)
**List Queues**
**Operation ID:** `queues-list`

Returns the queues owned by an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mq_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of all Queues that belong to this account |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
