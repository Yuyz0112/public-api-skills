# DELETE /accounts/{account_id}/event_subscriptions/subscriptions/{subscription_id}

**Resource:** [Queue](../resources/Queue.md)
**Delete Event Subscription**
**Operation ID:** `subscriptions-delete`

Delete an existing event subscription

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mq_identifier | Yes |  |
| `subscription_id` | path | mq_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully created event subscription |

## Security

- **api_email**
- **api_key**
- **api_token**
