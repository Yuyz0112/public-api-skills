# PATCH /accounts/{account_id}/event_subscriptions/subscriptions/{subscription_id}

**Resource:** [Queue](../resources/Queue.md)
**Update Event Subscription**
**Operation ID:** `subscriptions-patch`

Update an existing event subscription

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mq_identifier | Yes |  |
| `subscription_id` | path | mq_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully created event subscription |
| 400 | Invalid request body or validation errors |
| 404 | Queue does not exist or resource not found on source |

## Security

- **api_email**
- **api_key**
- **api_token**
