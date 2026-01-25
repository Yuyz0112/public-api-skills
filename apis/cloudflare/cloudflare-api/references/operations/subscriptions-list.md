# GET /accounts/{account_id}/event_subscriptions/subscriptions

**Resource:** [Queue](../resources/Queue.md)
**List Event Subscriptions**
**Operation ID:** `subscriptions-list`

Get a paginated list of event subscriptions with optional sorting and filtering

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mq_identifier | Yes |  |
| `page` | query | integer | No | Page number for pagination |
| `per_page` | query | integer | No | Number of items per page |
| `order` | query | enum: created_at, name, enabled... | No | Field to sort by |
| `direction` | query | enum: asc, desc | No | Sort direction |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of event subscriptions |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
