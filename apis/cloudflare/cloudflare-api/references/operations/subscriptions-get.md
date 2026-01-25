# GET /accounts/{account_id}/event_subscriptions/subscriptions/{subscription_id}

**Resource:** [Queue](../resources/Queue.md)
**Get Event Subscription**
**Operation ID:** `subscriptions-get`

Get details about an existing event subscription

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mq_identifier | Yes |  |
| `subscription_id` | path | mq_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Details about an event subscription |
| 404 | Event subscription does not exist |

## Security

- **api_email**
- **api_key**
- **api_token**
